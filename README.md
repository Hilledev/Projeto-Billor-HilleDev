# Projeto-Billor-HilleDev
Projeto-Billor-HilleDev

📌 Documentação do Aplicativo de Motorista
1️⃣ Visão Geral
Este projeto é um aplicativo móvel para motoristas, desenvolvido com Flutter e Firebase, seguindo os requisitos do projeto original, que pedia uma implementação em React Native. O app permite que motoristas:
Façam login e cadastro com autenticação via Firebase.
Visualizem e gerenciem cargas, escolhendo aquelas disponíveis.
Enviem imagens de documentos usando a câmera do dispositivo.
Comuniquem-se via chat em tempo real com o suporte e outros motoristas.
Recebam notificações push sobre novas cargas e mensagens no chat.
Gerenciem seu perfil, alterando nome, e-mail, telefone, senha e foto.

2️⃣ Tecnologias Utilizadas
Framework: Flutter
Gerenciamento de Estado: Riverpod
Autenticação: Firebase Authentication
Banco de Dados: Firebase Firestore
Armazenamento de Imagens: Firebase Storage
Mensagens em Tempo Real: Firebase Firestore + Firebase Cloud Messaging (FCM)
Notificações Push: Firebase Cloud Messaging
Mapas: Google Maps API
Upload de Imagens: Image Picker
UI/UX: Material Design com Widgets Personalizados

EMAIL E SENHA DE ACESSO DO SUPORTE

E-MAIL HILLEDEV90@GMAIL.COM
SENHA teste123


3️⃣ Estrutura do Projeto
O projeto está organizado da seguinte forma:
bash
CopiarEditar
/motorista_app
│── lib/
│   ├── main.dart
│   ├── screens/
│   │   ├── login_screen.dart
│   │   ├── home_screen.dart  
│   │   ├── cadastro_screen.dart
│   │   ├── cargas_screen.dart
│   │   ├── detalhes_carga_screen.dart
│   │   ├── minha_carga_screen.dart  
│   │   ├── perfil_screen.dart
│   │   ├── chat_screen.dart
│   │   ├── criar_carga_screen.dart  (somente ADMIN)
│   │   ├── suporte_chat_screen.dart  (somente ADMIN)
│   │   ├── suporte_lista_chat_screen.dart  (somente ADMIN)
│   ├── models/
│   │   ├── carga.dart
│   ├── services/
│   │   ├── carga_service.dart
│   ├── providers/
│   │   ├── auth_provider.dart
│   │   ├── carga_provider.dart
│   ├── utils/
│   │   ├── firebase_config.dart
│── android/ (Configuração do Firebase)
│── ios/ (Configuração do Firebase)
│── pubspec.yaml (Dependências)




4️⃣ Funcionalidades Implementadas
🔐 Autenticação
Login via Firebase Authentication.
Cadastro de motoristas com nome, e-mail, telefone e senha.
Recuperação de senha via e-mail.
📦 Gestão de Cargas
Listagem de cargas disponíveis no Firestore.
Exibição de detalhes da carga com status e localização no Google Maps.
Motorista pode escolher uma carga, alterando o status no Firestore.
📸 Envio de Documentos
Captura de imagens usando Image Picker.
Upload das imagens para o Firebase Storage.
💬 Bate-papo em Tempo Real
Chat em tempo real via Firebase Firestore.
Histórico de conversas salvo no Firestore.
Suporte pode visualizar todas as conversas.
🔔 Notificações Push
Firebase Cloud Messaging (FCM) envia alertas para:
Novas cargas disponíveis.
Mensagens do chat.
Atualizações da carga.
⚙️ Gerenciamento de Perfil
Alteração de nome, e-mail, telefone e senha via Firebase.
Upload e alteração de foto de perfil via Firebase Storage.
Tela organizada com botões separados para cada alteração.

