# web-app-canary-chart

## Note

Using 2 separate Services to trigger Canary Deployment

To enable Canary
```
helm upgrade --install --set canary_deployment=true myapp web-app-canary-chart/
```

To disable Canary
```
helm upgrade --install --set canary_deployment=false myapp web-app-canary-chart/
```
