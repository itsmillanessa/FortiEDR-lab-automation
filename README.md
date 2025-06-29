# FortiEDR Lab Automation

Este repo contiene dos templates CloudFormation:
- `fortiedr-lab.yaml`: Despliega VPC + EC2 Windows con AMI personalizada.
- `fortiedr-auto-destroy.yaml`: Lambda + EventBridge para eliminar el stack a las 2 horas.

## 🚀 Pasos

1. Desplegar:
```bash
aws cloudformation deploy \
    --template-file fortiedr-lab.yaml \
    --stack-name fortiedr-lab \
    --region us-west-1
