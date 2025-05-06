
# Relógio Digital em Python (Terminal)

Este projeto é um script simples em Python que exibe a hora atual no terminal, atualizando a cada segundo — como um relógio digital.

## 📄 Código

```python
import time

while True:
    hora_atual = time.strftime("%H:%M:%S")
    print(hora_atual, end="\r")
    time.sleep(1)
```

## ▶️ Como executar

1. Certifique-se de ter o Python instalado.
2. Copie o código para um arquivo chamado `relogio.py`.
3. No terminal, execute:

```bash
python relogio.py
```

Você verá a hora atual sendo exibida no mesmo lugar, atualizada a cada segundo.

## 📌 Observações

- O script usa a função `strftime` para formatar a hora no estilo `HH:MM:SS`.
- O `end="\r"` faz com que o cursor retorne ao início da linha, atualizando no mesmo lugar.
- O `time.sleep(1)` garante que a hora só seja atualizada uma vez por segundo.

## 👨‍💻 Autor

Feito por [Jessi James]
