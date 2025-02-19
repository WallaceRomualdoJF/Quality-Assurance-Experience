
# UI em Android com Kotlin e Espresso
**Teste de Automação**

O framework de testes Espresso oferece um conjunto de APIs para criar testes de interface do usuário (UI) e testar fluxos de usuário dentro de um aplicativo, permitindo escrever testes automatizados para a UI.

### Sobre este Projeto

Este projeto é desenvolvido para Android com a linguagem Kotlin, utilizando o framework **Espresso** para testes de UI. Ele oferece uma introdução básica aos testes automatizados de UI. O projeto contém:

- **Lançamento de Activity e Testes de Exibição**.
- **Encontrar Views e realizar ações em Views**, como Botões e digitação em EditText.
- **Testes de RecyclerView**.
- **Ações ou Testes em Menus e Menus de Sobrecarga (Overflow) no Android**.

### Passos para escrever o primeiro caso de teste de UI

1. **Criar o Teste usando JUnit4** (atualmente não há suporte para JUnit5)
   - Exemplo: `MainActivityTest`

2. **Lançar a Activity para cada caso de teste**
   - Exemplo: `ActivityScenario.launch(MainActivity::class.java)`

3. **Encontrar a View, ou seja, ViewMatcher**
   - Encontrar View por ID: `onView(withId(R.id.fab))`
   - Encontrar View por Texto: `onView(withText("SET ALARM"))`

4. **Executar Ação, como Click ou Digitação**
   - Exemplo: `.perform(click())`
   - Exemplo: `.perform(typeText("Olá, estou digitando um texto"))`

5. **Asserção de View**
   - Exemplo: Verifique se o estado atual da View está visível e, em seguida, passe este caso de teste: `.check(matches(isDisplayed()))`
