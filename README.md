# CONECT IA SKILLS

Colección de skills para Claude Code. Esta primera versión incluye **REELS AI STARTER**, una skill básica para analizar una marca y preparar Reels.

## Instalar REELS AI STARTER

Requisitos: Git y Claude Code instalados.

### macOS / Linux / Git Bash

```bash
git clone https://github.com/brunohidalgo75-droid/CONECT-IA-SKILLS.git
mkdir -p ~/.claude/skills
cp -R CONECT-IA-SKILLS/reels-factory ~/.claude/skills/
```

Si ya clonaste el repositorio, ejecuta solamente:

```bash
mkdir -p ~/.claude/skills
cp -R CONECT-IA-SKILLS/reels-factory ~/.claude/skills/
```

Reinicia Claude Code y escribe:

```text
/reels-factory
```

## ¿Qué hace?

1. Configura el perfil básico de tu marca.
2. Analiza Instagram si existe un conector/herramienta con acceso real; de lo contrario, trabaja con enlaces, capturas o datos que compartas.
3. Crea tres Reels: TOFU, MOFU y BOFU.
4. Entrega guiones, ganchos, textos en pantalla, sugerencias visuales y CTA.
5. Organiza una semana básica de contenido.

## Importante

- La skill no conecta Instagram por sí sola. Para analizar datos privados o métricas necesitas un conector compatible y autorizarlo.
- No publica ni programa contenido. Genera materiales para que los revises y publiques.
- No inventa estadísticas ni resultados.
- La instalación copia la carpeta de esta skill a tu directorio personal de skills de Claude Code.

Repositorio: https://github.com/brunohidalgo75-droid/CONECT-IA-SKILLS
