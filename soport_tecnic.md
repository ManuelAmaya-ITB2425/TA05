# Soporte tecnico

## Grupo 1

_En este apartado colocaremos **Zendesk Answer Bot** como referencia_


## Indice
1. [Les aplicacions de la IA](##Les_aplicacions_de_la_IA)
2. [Impacte al sector](##Impacte_al_sector)
3. [Impacte ambiental](##Impacte_ambiental)
4. [Propostes per minimitzar els impactes ambientals](##Propostes_per_minimitzar_els_impactes_ambientals)

---

## Las aplicaciones de la IA

>Zendesk Answer Bot es un chatbot avanzado basado en inteligencia artificial, diseñado específicamente para mejorar el soporte técnico en empresas con un alto volumen de consultas. Utilizando procesamiento de lenguaje natural (NLP), este sistema es capaz de entender el lenguaje humano y proporcionar respuestas rápidas y precisas a preguntas frecuentes. Sus aplicaciones incluyen:
> * **Respuestas automáticas:** Brinda respuestas instantáneas a consultas recurrentes relacionadas con problemas comunes
> * **Guías interactivas:** Ofrece instrucciones paso a paso para ayudar a los usuarios a resolver incidencias por sí mismos.
> * **Escalado a técnicos humanos:** Dirige consultas más complejas a usuarios, lo que permite a los técnicos centrarse en tareas más especializadas.
> * **Aprendizaje continuo** Mejora constantemente su capacidad de respuesta a medidaque interactúa con los usuarios, adaptándose a nuevas situaciones y aprendiendo en cada conversación.
## Impacte al sector

>El impacto de Zendesk Answer Bot en el sector del soporte técnico es profundo y ha transformado la manera en que se gestionan las interacciones con los clientes. Entre los efectos más destacados se encuentran:
> * **Reducción de la carga de trabajo humano:** Al automatizar tareas repetitivas y resolver consultas frecuentes, permite a los técnicos enfocarse en problemas más complejos, lo que incrementa su productividad.
> * **Mejora en la experiencia del cliente:** Los usuarios pueden recibir asistencia en cualquier momento del día sin necesidad de esperar por un agente, lo que mejora la satisfacción y reduce los tiempos de espera.
> * **Optimización de costos operativos:** Las empresas pueden reducir sus costos operativos, ya que necesitan menos personal humano para manejar las consultas básicas. Esto es especialmente valioso para empresas que operan a nivel global.
> * **Análisis y mejora continua:** Analiza grandes volúmenes de datos, identificando patrones y áreas de mejora en la atención al cliente, lo que optimiza los procesos internos y mejora la calidad del servicio.

## Impacte ambiental

>Como otros sistemas basados en IA, Zendesk Answer Bot consume energía para entrenar y ejecutar sus modelos, especialmente cuando está integrado en entornos en la nube. Esto contribuye a una huella de carbono, especialmente si los centros de datos utilizan fuentes de energía no renovables.

## Propostes per minimizar los impactos ambientales

> * Implementar centros de datos con certificación de energia renovable para alojar el servicio.
> * Optimitzar el codigo y los modelos de aprendizaje automatico para reducir la complejidad y el consumo energetico.
> * Adoptar practicas como el entrenamiento federado, que permite compartir datos entre sistemas sin transferirlos masivamente a la nube, reduciendo asi la carga de red y el consumo energetico.
> 
>> Esta herramienta no solo optimiza el soporte técnico para personas, sino que también tiene un potencial de mejora ambiental si se gestiona correctamente.



##Exemple de comanda que realitza Zendesk Answer Bot en el soport tècnic para automatizar las respuestas a los clientes.

```
<script type="text/javascript">
  window.zESettings = {
    webWidget: {
      answerBot: {
        suppress: false,
        title: {
          '*': 'Chat with us!'
        },
        contactOnlyAfterQuery: true,
        search: {
          labels: ['I would like help.']
        },
        avatar: {
          url: '#exemple',
          name: {
            '*': 'Company logo'
          }
        }
      }
    }
  };
</script>
```
