# Pix Transfer System

Sistema bancário para transferências via PIX.

## Funcionalidades
- 🔹 Criar conta bancária com senha segura
- 🔹 Realizar transferências PIX
- 🔹 Consultar saldo e histórico de transações
- 🔹 Gerar comprovantes de pagamento em PDF
- 🔹 Recuperação de senha segura

```
def encontrar_conta_por_pix(contas, chave_pix):
    for conta in contas:
        if conta.chave_pix == chave_pix:
            return conta
    return None
```

## Como Executar
1. Clone o repositório:
   ```sh
