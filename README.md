🕒 Auto-Destructible Lab
fortiedr-lab-autodestroy-4h.yaml
Este template de CloudFormation lanza un entorno completo para pruebas de FortiEDR sobre Windows con:

VPC y subred pública

EC2 con tu AMI personalizada (ami-0bd727d0f2cc37f98)

Security Group con acceso RDP (puerto 3389)

Lambda + EventBridge que autodestruyen el stack 4 horas después del despliegue

🚀 Uso
Ve a AWS CloudFormation

Clic en “Crear pila” > “Con recursos nuevos (estándar)”

Carga el archivo fortiedr-lab-autodestroy-4h.yaml

Da clic en “Siguiente” → “Siguiente” → Acepta permisos IAM → Crear pila

🕓 La pila se eliminará automáticamente en 4 horas sin intervención manual.
