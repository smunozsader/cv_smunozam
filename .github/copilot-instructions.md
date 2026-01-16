## **Copilot Instructions – CV de Sergio Muñoz**

## **Descripción del Proyecto**

Workspace profesional de Sergio Muñoz de Alba Medrano para mantener un currículum vitae bilingüe (español/inglés) y textos asociados (LinkedIn, cartas de motivación) orientados a posiciones de dirección de operaciones, gestión de programas y Chief of Staff / Desarrollo Organizacional en sectores público, social y privado con misión.

## **Estructura de Archivos**

text

`*SPA*.md → CV versión español (documento fuente narrativo)`  
`*ENG*.md → CV versión inglés (traducción sincronizada)`  
`cv-sergio-munoz-eng.tex → Versión LaTeX (moderncv) para PDF`  
`copilot-instructions.md → Este archivo de contexto y reglas`  
`docs_profesionales/ → Documentos oficiales (título, cédula, reconocimientos, etc.)`

## **Objetivo Laboral Actual**

Posicionar a Sergio Muñoz de Alba Medrano como:

-   Director de Operaciones / Programas
-   Chief of Staff / Coordinador de Despacho
-   Director de Desarrollo Organizacional / Administración

en organizaciones públicas, no gubernamentales o privadas con enfoque en impacto (desarrollo regional, servicios, educación, sostenibilidad, etc.), preferentemente con base en Mérida o Península de Yucatán.

La experiencia en agricultura, sanidad animal y conservación se usará como dominio de especialidad, pero el mensaje principal es: líder de operaciones y gestión que puede trabajar en distintos sectores.

## **Reglas de Edición**

## **Tono y Estilo**

-   Tono profesional, claro y directo, no excesivamente burocrático.
-   En español: lenguaje neutro, apto para sector público, ONG y empresa.
-   En inglés: business / managerial tone (operations, leadership, execution).
-   Evitar encasillar el perfil sólo en “sector agropecuario” o “conservación”; siempre enmarcarlo como gestión de operaciones y programas.

## **Enfoque de Contenido**

Al reescribir o generar secciones del CV o LinkedIn, Copilot debe:

1.  Presentar a Sergio principalmente como:
    -   Líder de operaciones y programas.
    -   Perfil tipo Chief of Staff / mano derecha de dirección.
    -   Experto en ejecución, coordinación y estructura organizacional.
2.  Usar la conservación y el desarrollo rural como ejemplos de contextos, no como única identidad profesional.
3.  Destacar sistemáticamente:
    -   Tamaño de equipos dirigidos (hasta 320+ personas, 22 oficinas).
    -   Tamaño de presupuestos manejados (250+ MDP, 120 MDP/año, 45,000+ beneficiarios).
    -   Roles de coordinación interinstitucional y de enlace con alta dirección.
    -   Diseño e implementación de procesos, SOPs, sistemas de seguimiento y plataformas digitales.
4.  Adaptar la narrativa de cada puesto para que suene a:
    -   Dirección / coordinación de operaciones.
    -   Planificación y ejecución de programas.
    -   Gestión de información, indicadores, reportes y cumplimiento.

## **Sincronización Bilingüe**

-   Cada cambio relevante en español debe reflejarse en la versión en inglés (*SPA* ↔ *ENG*).
-   Mantener estructura lo más paralela posible entre ambos idiomas.
-   Traducciones orientadas a management:
    -   “Subdelegado de Planeación y Desarrollo Rural” → “Deputy Director for Planning and Rural Development (Operations Lead)”.
    -   “Encargado del Despacho” → “Acting Head / Acting Regional Director”.

## **Formato del CV (LaTeX)**

-   Seguir usando clase moderncv (estilo banking, color azul).
-   Orden cronológico inverso.
-   Cada experiencia profesional debe incluir:
    -   1–2 frases de contexto (rol en términos de operaciones/gestión).
    -   3–5 viñetas con logros cuantificados (personas, presupuesto, alcance, sistemas implementados).
-   Incluir secciones:
    -   Professional Summary / Resumen Profesional centrado en operaciones.
    -   Core Management Competencies / Competencias Clave de Gestión.
    -   Professional Experience / Experiencia Profesional.
    -   Education, Languages, Technical Skills.

## **Competencias Clave a Destacar**

Actualizar la tabla mental de competencias hacia management general:

Competencia

Evidencia Cuantificable / Descriptiva

Liderazgo de operaciones

Dirección de 320+ personas y 22 oficinas (SAGARPA).

Gestión de programas

Manejo de 250+ MDP anuales, 45,000+ beneficiarios.

Chief of Staff / Enlace

Encargado del despacho de Delegación, coordinación con gobierno estatal y federación.

Desarrollo organizacional

Creación de consejos municipales, comunidades de práctica, equipos interinstitucionales.

Procesos y calidad

Implementación de SOPs, participación en ISO 9000, estandarización de flujos.

Datos y sistemas

Plataformas GOB.mx v3, sistemas de trazabilidad y de seguimiento de acuerdos.

Relación con stakeholders

Trabajo con secretarías, organismos internacionales, productores y sector privado.

## **Instrucciones Específicas para Copilot en VS Code**

Cuando se use Copilot sobre los archivos:

1.  En cv-sergio-munoz-eng.tex:
    -   Reescribir la sección Professional Summary para que hable de:
        -   “Operations and Program Management Leader”
        -   “Chief of Staff–style support to senior leadership”
        -   “Large-scale teams and budgets”.
    -   Reescribir Key Administrative Competencies como Core Management Competencies con foco en operaciones, estrategia y organización.
    -   Ajustar cada cventry para:
        -   Comenzar con una frase que explique el rol en términos de dirección/operaciones.
        -   Modificar viñetas para que destaquen gestión, coordinación, procesos, sistemas y resultados medibles.
2.  En los archivos *SPA*.md y *ENG*.md:
    -   Mantener versiones narrativas del CV que luego se vuelcan a LaTeX.
    -   Usar exactamente el mismo enfoque de posicionamiento (operations / Chief of Staff).
3.  Para LinkedIn (archivo nuevo opcional: linkedin-profile.md):
    -   Generar:
        -   Un headline orientado a “Director of Operations / Program Management / Chief of Staff”.
        -   Un About que resuma 30+ años de experiencia en liderazgo de operaciones, presupuestos y coordinación de actores.
        -   Descripciones de puestos en formato breve, con foco en resultados y escala.

## **Formato de Salida**

-   CV oficial: cv-sergio-munoz-eng.tex compilado a PDF desde VS Code (latexmk / pdflatex).
-   Texto base LinkedIn: linkedin-profile.md para copiar/pegar en la plataforma.
-   Cartas de motivación: documentos Markdown específicos por vacante, pero siempre coherentes con la narrativa de liderazgo de operaciones.

## **Idioma de Interacción**

-   Con Copilot y en archivos internos se puede trabajar en español, salvo secciones explícitamente marcadas como inglés.
-   El contenido final del CV en inglés debe usar terminología estándar de management (Operations Director, Program Director, Chief of Staff, etc.).