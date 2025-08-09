### Install Linux
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

### Version
```bash
uv --version
```

### Create project
```bash
uv init
uv init my-app-uv
```

### Estructura Inicial
	pyproject.toml	similar a requirements.txt

### Ejecutar projecto
```bash
uv run main.py
uv run fastapi dev main.py
uv run uvicorn main:app --reload
```

### Agregar dependencias
```bash
uv add fastapi
```

### Agregar dependencias de desarrollo
```bash
uv add --dev pytest
```

### Eliminar dependencias
```bash
uv remove redis
```

### Listar dependencias
```bash
uv tree
```

### Instalar dependencias
```bash
uv sync
```

### Instalar globalmente
```bash
uv tool install ruff
wich ruff
```

### Desinstalar globalmente
```bash
uv tool unnistall ruff
wich ruff
```

### Ejecutar herramientas Python sin instalarlas globalmente
```bash
uvx black main.py
```

### Lista instalaciones globales
```bash
uv tool list
```

### Actualizar instalaciones globales
```bash
uv tool upgrade --all
```