COMO USAR NO CELULAR

1. Crie um repositório no GitHub.
2. Envie todos os arquivos deste ZIP para a raiz do repositório.
3. O arquivo .github/workflows/android.yml já faz a compilação automática.
4. No GitHub, abra a aba Actions.
5. Execute o workflow "Build APK" ou faça um commit na branch main.
6. Quando terminar, abra a execução e baixe o artefato "reduto-base-debug-apk".

OBSERVAÇÕES IMPORTANTES
- Este projeto é uma base Java simples, pensada para facilitar a compilação no GitHub Actions.
- Eu não consegui validar a compilação neste ambiente porque ele não tem o Android SDK/Gradle completos instalados.
- Se o GitHub acusar erro de SDK/plugin, normalmente basta manter a estrutura e ajustar a versão do plugin Android no arquivo build.gradle.
- O backend PHP de exemplo está na pasta backend/.

LOGIN DE TESTE
- usuário: admin
- senha: 123456
