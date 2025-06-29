# FortiEDR Lab Automation

Este repo contiene dos templates CloudFormation:
- `fortiedr-lab.yaml`: Despliega VPC + EC2 Windows con AMI personalizada.
- `fortiedr-auto-destroy.yaml`: Lambda + EventBridge para eliminar el stack a las 2 horas.

## 👥 requerimientos para ejecutar:

Para que puedas lanzar este lab:

1. Asegúrate de que tu cuenta AWS tenga permisos necesarios.
2. Solicita que tu cuenta esté autorizada para usar la AMI `ami-0cdd0c1de5ebe61d1` (contacta a @amillan).
3. Sigue los pasos arriba descritos para desplegar ambos stacks.




## 🚀 Pasos

1. Desplegar:
```bash
aws cloudformation deploy \
    --template-file fortiedr-lab.yaml \
    --stack-name fortiedr-lab \
    --region us-west-1
