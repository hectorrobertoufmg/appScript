# Remove Duplicate Enrollments

Esta função em JavaScript foi projetada para ser utilizada em uma planilha do Google Sheets. Ela automatiza a tarefa de remover matrículas duplicadas com base nos valores da coluna "C" da planilha.

## Como usar

1. Abra sua planilha no Google Sheets.

2. Na planilha, vá para **Extensões > Apps Script** para abrir o editor de scripts do Google Apps Script.

3. Cole o código da função `removeDuplicateEnrollments` no editor.

4. Salve o projeto com um nome apropriado, se necessário.

5. Execute a função selecionando-a no editor e clicando no ícone de seta de execução (▶️).

A função irá percorrer sua planilha e remover todas as linhas duplicadas com base nos valores da coluna "C". Após a execução bem-sucedida, sua planilha não deve mais conter matrículas duplicadas.

## Notas importantes

- Certifique-se de fazer um backup da sua planilha antes de usar esta função, pois a remoção de linhas é irreversível.

- Esta função considera como duplicatas as matrículas que têm valores idênticos na coluna "C". Portanto, certifique-se de que essa coluna contenha os dados que você deseja verificar para duplicatas.

- Lembre-se de ajustar as permissões de acesso da planilha conforme necessário para executar scripts do Google Apps Script.

## Autor

Esta função foi desenvolvida por Hector Roberto e está disponível gratuitamente para uso e personalização.

Este README foi gerado pelo modelo de linguagem GPT-3.5 da OpenAI.

