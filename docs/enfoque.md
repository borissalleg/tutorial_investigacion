El enfoque en la investigación es el marco filosófico, teórico o conceptual que guía cómo se aborda un estudio. Define la perspectiva desde la cual se interpreta la realidad, se plantean las preguntas y se seleccionan los métodos. Es la "visión" que sustenta todo el proceso de investigación y determina cómo se relaciona el investigador con el objeto de estudio.


???+ note "¿Qué comprende el enfoque?"
    ???+ info "1.   Paradigma filosófico"
        Define cómo se entiende el conocimiento (epistemología), la realidad (ontología) y los valores (axiología).

        -   Positivismo
        -   Constructivismo
        -   Enfoque crítico.

    ???+ info "2.  Estrategia metodológica "

        Indica si el estudio será

        -   Cualitativo
        -   Cuantitativo 
        -   Mixto , y cómo se adaptan a los objetivos.

    ???+ info "3.   Perspectiva teórica"

    Las teorías o conceptos que sustentan la investigación (ej.: teoría de género, teoría del caos).
  
=== "Enfoque general"
     Es el marco teórico y práctico que guía la investigación (ej.: enfoque cualitativo, cuantitativo o mixto).
     
    === "Metodologías Cualitativas"
        Se centran en comprender significados, experiencias y perspectivas subjetivas.

        ???+ info "Etnografía"
              Estudia grupos culturales o comunidades en su entorno natural.
           
        ???+ info "Estudio de caso" 
              Análisis profundo de un individuo, grupo, organización o evento.
            
        ???+ info "Fenomenología"
              Explora la esencia de experiencias vividas por personas.
            
        ???+ info "Teoría fundamentada (Grounded Theory)"
               Genera teorías a partir de datos recopilados.
            
         ???+ info "Investigación narrativa "
               Analiza historias o relatos personales.

         ???+ info "Investigación acción participativa"
               Busca transformar realidades sociales con la participación de los involucrados.


    === "Metodologías Cuantitativas"

            Se basan en datos numéricos y análisis estadístico para probar hipótesis.

            Experimental : Manipula variables para establecer relaciones causa-efecto (ej.: ensayos controlados).
            Cuasiexperimental : Estudia causas sin asignación aleatoria (ej.: estudios con grupos intactos).
            Correlacional : Mide la relación entre variables sin manipulación.
            Descriptiva : Describe características de una población o fenómeno (ej.: encuestas).
            Longitudinal : Analiza cambios a lo largo del tiempo (ej.: seguimiento de cohortes).
            Transversal : Recoge datos en un solo momento (ej.: estudios epidemiológicos).
              
    === "Metodologías Mixtas (Mixtas Methods)"

        Combinan enfoques cualitativos y cuantitativos:

        Exploratoria secuencial : Primero cualitativa, luego cuantitativa.
        
        Explicativa secuencial : Primero cuantitativa, luego cualitativa.
        
        Convergente : Ambos métodos se usan en paralelo y se integran en el análisis.


<!--             
            4. Otras Metodologías Específicas
            Investigación acción : Busca resolver problemas prácticos con participación activa de los actores.
            Estudio longitudinal : Sigue a sujetos durante un período prolongado.
            Metaanálisis : Sintetiza resultados de múltiples estudios cuantitativos.
            Revisión sistemática : Evalúa y resume evidencia existente sobre un tema.
            Investigación histórica : Analiza eventos pasados mediante fuentes primarias/secundarias.
            Delphi : Consenso de expertos mediante rondas de consultas anónimas.


=== "Procedimientos específicos"
        Incluye técnicas como encuestas, entrevistas, experimentos, observación, etc.
=== "Justificación"
        Explica por qué se eligieron ciertos métodos y cómo se adaptan a los objetivos del estudio.

## Elección de la Metodología
Depende de:

Objetivos de la investigación.
Pregunta de estudio (exploratoria, descriptiva, explicativa).
Recursos disponibles (tiempo, financiamiento, acceso a datos).
Paradigma filosófico (positivismo, constructivismo, crítico). -->

```mermaid
mindmap
  root((Metodologías de Investigación))
    Enfoque General
      Cuantitativo
      Cualitativo
      Mixto
    Subtema 2
      Punto C
      Punto D

```
%% Definir colores
  classDef principal fill:#FFD700,stroke:#333,stroke-width:2px,font-weight:bold;
  classDef nivel1 fill:#FF5733,stroke:#333,stroke-width:2px,color:white;
  classDef nivel2 fill:#3498DB,stroke:#333,stroke-width:2px,color:white;

```mermaid
mindmap
    root((Metodologías de Investigación)):::principal
        Enfoque General:::nivel1
            Cualitativo:::nivel2
            Cuantitativo:::nivel2
            Mixto:::nivel2
```


```mermaid
graph TD

    A[Inicio] --> B{¿Condición?}

    A(((Metodologías de Investigación)))
    A --> B(Enfoque general)
    B --> B1((Cualitativo))
    B --> B2((Cuantitativo))
    B ---> E(( Mixtas))
    E --> E1(Exploratoria secuencial)
    E1 --> E1a((Primero cualitativa, luego cuantitativa))
    E --> E2(Explicativa secuencial)
    E2 --> E2a((Primero cuantitativa, luego cualitativa))
    E --> E3(Convergente)
    E3 --> E3a(((Ambos métodos en paralelo, integración en análisis)))
```

 
```markdown
    ```mermaid
    mindmap
    root((Metodologías de Investigación)):::raiz
        Enfoque General:::categoria
        Cualitativo:::subcategoria
        Cuantitativo:::subcategoria
        Mixto:::subcategoria
        
        Metodologías Cualitativas:::categoria
        Etnografía:::tema
        Estudio de Caso:::tema
        Fenomenología:::tema
        Teoría Fundamentada:::tema
        Investigación Narrativa:::tema
        Investigación Acción Participativa:::tema

        Metodologías Cuantitativas:::categoria
        Experimental:::tema
        Cuasiexperimental:::tema
        Correlacional:::tema
        Descriptiva:::tema
        Longitudinal:::tema
        Transversal:::tema

        Metodologías Mixtas:::categoria
        Exploratoria Secuencial:::tema
        Explicativa Secuencial:::tema
        Convergente:::tema
```
%% Definir estilos
  classDef raiz fill:#ffcc00,stroke:#333,stroke-width:2px,font-weight:bold;
  classDef categoria fill:#ff6666,stroke:#333,stroke-width:2px,color:white;
  classDef subcategoria fill:#66ccff,stroke:#333,stroke-width:2px,color:white;
  classDef tema fill:#99ff99,stroke:#333,stroke-width:2px;
