<<<<<<< HEAD
#  Flask Pix Payment API

Este projeto é uma API Flask que simula a criação de pagamentos via Pix. A cada pagamento criado, um QR Code exclusivo é gerado e pode ser visualizado por meio de uma rota dedicada.

---

##  Funcionalidades

- Criar um pagamento via Pix (`POST /payments/pix`)
- Visualizar os dados de um pagamento (`GET /payments/pix/<payment_id>`)
- Gerar e visualizar o QR Code correspondente (`GET /payments/pix/qr_code/<file_name>`)
- Página HTML com os detalhes do pagamento + QR Code renderizado

---

##  Demonstração

### Exemplo de resposta:
```json
{
  "message": "the payment has been created",
  "payment": {
    "id": 1,
    "value": 500.0,
    "paid": false,
    "bank_payment_id": "uuid-gerado",
    "qr_code": "qr_code_payment_uuid.png",
    "expiration_date": "2025-07-14T14:00:00"
  }
}
=======
>>>>>>> 1ff2ae2 (finish project)
