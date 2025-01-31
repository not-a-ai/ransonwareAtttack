# 🛑 Simulação de Ataque Ransomware com Python  

Este projeto demonstra um **exercício educacional** sobre como um ransomware pode criptografar e descriptografar arquivos usando Python e a biblioteca `pyaes`. **Este código deve ser usado apenas para fins educacionais e de aprendizado sobre segurança cibernética.**

## ⚠️ Aviso Legal  

**Este projeto é apenas para fins educacionais!**  
Não utilize este código para atividades mal-intencionadas. O uso indevido pode ser considerado crime, sujeito a penalidades conforme a legislação aplicável.

---

## 📌 Sobre o Projeto  

O projeto contém dois scripts principais:  

- **`encrypto.py`** → Responsável por criptografar um arquivo `text.txt`, removendo o original e criando uma versão criptografada.  
- **`decrypto.py`** → Utilizado para descriptografar o arquivo anteriormente criptografado, restaurando-o ao formato original.  

A criptografia é feita utilizando o **AES (Advanced Encryption Standard)** no modo **CTR (Counter Mode)**.

---

## 🚀 Como Usar  

![Execução dos códigos](projectransomware.png)

### 1️⃣ Instalação das Dependências  

Certifique-se de ter o **Python** instalado (versão 3+). Em seguida, instale a biblioteca `pyaes`:

```sh
pip install pyaes
```

### 2️⃣ Executando a Criptografia
Para criptografar o arquivo text.txt, execute:

```sh
python encrypto.py
```

Isso irá remover o arquivo original e gerar um novo arquivo criptografado chamado text.txt.ransomwaretroll.

### 3️⃣ Executando a Descriptografia
Para restaurar o arquivo original, execute:

```sh
python decrypto.py
```



