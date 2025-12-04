# Feira Digital - MVP (Flutter)

Repositório com o esqueleto do aplicativo **Feira Digital de Negócios Locais**.
Esta versão contém:
- Estrutura organizada por arquivos (screens, models, services, widgets).
- Integração preparada para Firebase (placeholders e instruções).
- Exemplo de telas: Login, Home, Cadastro de Produto, Listagem, Troca/Venda.

## Como usar

1. Instale o Flutter e ferramentas necessárias: https://flutter.dev/docs/get-started/install
2. Clone este repositório ou extraia o ZIP.
3. No terminal, execute:
   ```bash
   flutter pub get
   ```
4. Configure o Firebase para Android/iOS seguindo:
   - https://firebase.flutter.dev/docs/overview
   - Ou execute `flutterfire configure` (recomendado) para gerar os arquivos de configuração automaticamente.
5. Substitua os arquivos de configuração:
   - Android: `android/app/google-services.json`
   - iOS: `ios/Runner/GoogleService-Info.plist`

### Observações sobre Firebase
Neste projeto os serviços Firebase possuem implementações de exemplo e placeholders.
Você precisa:
- Criar um projeto no Firebase console.
- Ativar Authentication (Email/Password).
- Criar um Firestore (modo de teste inicialmente).
- Habilitar Firebase Storage se quiser upload de imagens.

### Executar
Com emulador ou dispositivo conectado:
```bash
flutter run
```

### Estrutura
```
lib/
  main.dart
  screens/
  models/
  services/
  widgets/
assets/
README.md
pubspec.yaml
```

Se quiser, eu posso:
- Gerar o arquivo ZIP pronto para download (já disponível).
- Instruir passo a passo para executar o `flutterfire configure`.
- Gerar uma série de commits e mensagens (arquivo `COMMITS.md`) para você usar no GitHub.

