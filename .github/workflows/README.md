# Godot Windows Template Builder

Build automatizado de plantillas de exportación de Godot 4.5.1 para Windows con encriptación habilitada.

## 🚀 Cómo usar

1. Ve a la pestaña **"Actions"**
2. Selecciona el workflow **"Build Godot Windows"**
3. Haz clic en **"Run workflow"** (botón verde)
4. Espera ~20-30 minutos a que termine
5. Descarga los archivos desde **"Artifacts"**

## 📁 Archivos generados

- `windows_template.exe` - Plantilla de exportación 64-bit
- `encryption_key.txt` - Clave de encriptación (¡GUÁRDALA!)

## 🔧 Cómo instalar en Godot

1. Descarga el artifact
2. Extrae `windows_template.exe`
3. Cópialo a:
Windows: C:\Users[TuUsuario]\AppData\Roaming\Godot\export_templates\4.5.1.stable
Linux: ~/.local/share/godot/export_templates/4.5.1.stable/
macOS: ~/Library/Application Support/Godot/export_templates/4.5.1.stable/

text
4. En Godot: Editor → Editor Settings → Export → Templates

## 🔐 Uso de encriptación

1. Al exportar tu juego, ve a la pestaña **"Encryption"**
2. Pega la clave del archivo `encryption_key.txt`
3. Marca **"Encrypt PCK"**
