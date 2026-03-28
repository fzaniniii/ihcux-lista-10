# 📱 FilaZero - Protótipo de Baixa Fidelidade

## 👤 Aluno
Fábio Henrique Zanini Ferreira

---

## 💡 Descrição da Ideia

O FilaZero é um aplicativo que permite que usuários evitem filas em estabelecimentos físicos, possibilitando visualizar locais próximos, verificar o tempo de espera e entrar virtualmente na fila.

O foco do projeto é melhorar a experiência do usuário, reduzindo tempo de espera e trazendo mais previsibilidade no atendimento.

---

## 🧩 Telas Criadas

Com base no protótipo desenvolvido, foram criadas as seguintes telas:

1. **Login**  
Tela de entrada do usuário no sistema.

2. **Cadastro**  
Permite que novos usuários criem uma conta.

3. **Home**  
Exibe estabelecimentos próximos com tempo estimado de espera.

4. **Detalhes do Estabelecimento**  
Mostra informações do local selecionado.

5. **Fila (Entrada na fila)**  
Permite que o usuário entre na fila virtual.

6. **Status da Fila**  
Mostra a posição do usuário e o tempo estimado.

7. **Avaliação**  
Permite avaliar a experiência após o atendimento.

---

## 🔄 Fluxo Principal do Usuário

O fluxo principal do sistema segue o seguinte caminho:

Login → Home → Detalhes → Entrar na fila → Status → Avaliação

---

## ⚠️ Fluxos Alternativos (UX Avançado)

Para melhorar a experiência do usuário, foram considerados cenários adicionais:

### ❌ Fila Cheia (Erro)
Caso o estabelecimento esteja lotado:
Detalhes → Fila → **Status Erro (Fila cheia)**

---

### 🚫 Cancelamento da Fila
O usuário pode sair da fila a qualquer momento:
Status → Cancelar → **Fila Cancelada**

---

### 🔁 Retorno ao Sistema
Após ações como erro ou cancelamento:
Usuário pode retornar para a **Home** e escolher outro estabelecimento.

---

### ✅ Confirmação de Entrada
Após entrar na fila:
Fila → **Status 2 (Confirmação de entrada)**

---

## 🧠 Foco em UX

Durante a prototipagem foram aplicados conceitos importantes de UX:

- **Visibilidade do status** (posição na fila e tempo de espera)  
- **Prevenção de erros** (tratamento de fila cheia)  
- **Controle do usuário** (possibilidade de cancelar a fila)  
- **Fluxo claro de navegação** entre telas  

---

## 📸 Protótipo

Os arquivos do protótipo estão disponíveis na pasta `/prototipo`:

- `prototipo.png`
- `prototipo.pdf`

## 📸 Visual do Protótipo

![Protótipo FilaZero](./prototipo/prototipo.png)
