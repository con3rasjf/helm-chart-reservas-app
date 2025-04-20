
# 🎼 Helm Chart – Reservas App
Este repositorio contiene el Helm Chart y los manifiestos necesarios para desplegar una aplicación fullstack en un clúster de Kubernetes local utilizando Minikube. La aplicación permite la reserva de salas de ensayo musicales y está compuesta por:

## 🌐 Estructura del proyecto

```
helm-chart-reservas-app/
├── charts/
│   └── rehearsal/             # Helm Chart principal de la aplicación
│       ├── Chart.yaml         # Metadatos del chart
│       ├── values.yaml        # Valores por defecto
│       └── templates/         # Plantillas de manifiestos Kubernetes
│           ├── deployment.yaml
│           ├── service.yaml
│           ├── ingress.yaml
│           └── ...
---
```

## 🎥 Tutorial paso a paso

Puedes ver cómo desplegar este proyecto completo (incluyendo ArgoCD, Ingress y sincronización GitOps) en el siguiente video:  
🔗 [https://www.youtube.com/watch?v=aHCDrAbH_go&t=939s](https://www.youtube.com/watch?v=aHCDrAbH_go&t=939s)

---

## 🙌 Autor
Proyecto desarrollado por [**Felipe Contreras**](https://www.linkedin.com/in/felipe-contreras-36834313a/)  