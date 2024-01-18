# TypeScript Curso 3 - Estrutura Atualizada do Projeto

## 🔄 Atualização na Estrutura do Projeto

1. **Abrindo no Visual Studio Code:**
   - Abra o Visual Studio Code, o editor utilizado durante o treinamento.
   - Vá até a área de trabalho e abra o projeto TypeScript do curso.

2. **Alteração na Estrutura:**
   - A pasta `dist` e `app`, que anteriormente continham o código-fonte, agora estão dentro de `app/src`.
   - A modificação foi feita para alinhar a estrutura com a de servidores web ou aplicações Angular e React.

3. **Requisitos de Infraestrutura:**
   - Certifique-se de ter o Node.js 10.21 ou superior (versões LTS), Visual Studio Code e o Chrome instalados.

4. **Executando o Projeto:**
   - Utilize o script `npm run start` para rodar o servidor local e o compilador TypeScript em tempo real.
   - O navegador será aberto automaticamente, refletindo as mudanças nos arquivos TypeScript em tempo real.

5. **Observações:**
   - A aplicação continua funcionando perfeitamente em relação ao curso anterior, sem alterações de código, apenas na estrutura de pastas.
   - O endereço agora será `localhost:3000/dist` e dentro dela estará o `index.html`.

6. **Código Fonte e Compilação:**
   - O código-fonte está na pasta `src` (source).
   - Os resultados da compilação do script `start` estarão na pasta `dist`.

7. **Index.html Adicional:**
   - O `index.html` dentro da pasta `app` serve como redirecionamento quando o servidor é aberto para a pasta `dist`.

Esta atualização na estrutura visa motivar uma abordagem específica ao longo do treinamento. Estamos prontos para começar e explorar as novidades para tornar o código cada vez mais elegante!