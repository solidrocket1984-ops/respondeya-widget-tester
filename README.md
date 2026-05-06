# RespondeYA Widget Tester

Site público estático para probar widgets de RespondeYA. Una sola página HTML/CSS/JS vanilla, sin frameworks.

## Cómo usar

1. Copia el snippet desde `panel.respondeya.es → Canales → Instalar widget en tu web`.
2. Pégalo en el textarea, pulsa **Cargar widget**.
3. El widget aparece abajo a la derecha. Habla con el agente.

## Validar dominios autorizados (F2.4)

Si tu workspace tiene `allowed_domains` configurado:
- El dominio del tester (`*.vercel.app` o el custom domain del deploy) debe estar autorizado.
- Cuentas demo tienen `'*'` (wildcard) por defecto.

## Stack

- HTML + CSS + JS vanilla
- Sin build step
- Deploy: `vercel --prod`

## Desarrollo local

```bash
# Cualquier servidor estático funciona
npx serve .
# o
python3 -m http.server
```
