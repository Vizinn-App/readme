# Vizinn App – O Marketplace Hiperlocal para Condomínios e Regiões Próximas

## 🏡 Sobre o Projeto

O **Vizinn** é uma plataforma inovadora que conecta moradores de condomínios e usuários em regiões específicas para compra, venda e oferta de serviços de forma prática e segura. Nosso objetivo é fortalecer a economia local e criar um ambiente confiável para transações entre vizinhos e comunidades próximas.

## 🚀 Foco Inicial

Lançamento no Nordeste do Brasil 
O usuário poderá definir a área de interesse, permitindo transações dentro de seu condomínio ou em locais estratégicos, como universidades, centros comerciais e bairros específicos.

## 📌 Funcionalidades Principais

- **Marketplace Exclusivo** – Apenas moradores verificados ou usuários em regiões próximas podem anunciar e comprar.
- **Anuncios Destaques** – O usuário poderá pagar pra destacar seu anúncio, e aparecer de alguma outra forma no app.
- **Filtros de Localização Inteligente** – Busque produtos e serviços dentro do seu condomínio ou em áreas específicas, como universidades, bairros e pontos de interesse.
- **Área de Trocas e Doações** – Incentivo à economia circular dentro das comunidades.
- **Painel para Síndicos** – Avisos, regras do condomínio e organização de eventos.
- **Avaliações e Reputação** – Sistema de feedback para aumentar a confiança entre os usuários.
- **Segurança e Moderação** – Denúncia de anúncios inadequados e validação de identidade.
- **Opção de Pagamento Integrado** – Facilitando transações seguras dentro do app.
- **Solicitações Específicas** – Usuários podem publicar demandas específicas, como "Quero um almoço na UFRN", permitindo que fornecedores locais atendam essas necessidades.

## Tecnologias Usadas

### Front-End (Typescript)

- **React Native**: Framework para construção de aplicações móveis nativas.
- **Ignite**: Boilerplate para acelerar o desenvolvimento de apps React Native com boas práticas.
- **TypeScript**: Linguagem de programação que adiciona tipagem estática ao JavaScript.
- **Axios**: Biblioteca para fazer requisições HTTP.
- **React Navigation**: Navegação para a aplicação.

### Back-End (Python)

- **FastAPI**: Framework moderno e rápido para construção de APIs RESTful.
- **Prisma**: ORM moderno e eficiente para trabalhar com bancos de dados SQL.
- **JWT**: Para autenticação e autorização de usuários.
- **PostgreSQL**: Banco de dados relacional para armazenar dados da aplicação.

### **Outras Tecnologias**

- WebSockets para atualizações em tempo real
- CI/CD para deploy automatizado

## 💡 Oportunidade de Investimento

O **Vizinn App** resolve um problema real e atende a uma demanda crescente por soluções hiperlocais. Estamos buscando investidores para expandir nossa base de usuários e desenvolver novas funcionalidades.

- **Modelo de Receita:** Anúncios segmentados, comissão sobre vendas e planos premium para serviços profissionais.
- **Mercado Potencial:** Milhares de condomínios e bairros estratégicos em Natal - RN e região com necessidade de soluções de comércio local.
- **Diferencial Competitivo:** Segurança, comunidade ativa e experiência otimizada para usuários.

## 📩 Contato

Se você deseja apoiar essa iniciativa ou fazer parte do projeto, entre em contato:
- **Email:** vizinn.app@gmail.com

---

# Funcionalidades Essenciais do MVP  

## ✅ 1. Cadastro e Login  
🔹 **Objetivo:** Garantir que apenas moradores ou usuários da região tenham acesso à plataforma.  

### 📌 Funcionalidades:  
- Cadastro por e-mail e senha ou login com Google/Facebook.  
- Validação via código SMS/e-mail para garantir a identidade do usuário.  
- Possibilidade de confirmar residência via código do condomínio (caso aplicável).  
- Perfil básico do usuário (nome, foto, localização e breve descrição).  

### 🔧 Tecnologias sugeridas:  
Firebase Authentication, OAuth (para login social), Twilio (para SMS).  

---

## ✅ 2. Marketplace Hiperlocal  
🔹 **Objetivo:** Permitir que moradores comprem e vendam produtos/serviços entre si de forma prática.  

### 📌 Funcionalidades:  
- Criar anúncios com título, descrição, preço e fotos.  
- Seleção de categoria (ex.: Eletrônicos, Serviços, Móveis, Alimentação, etc.).  
- Visualização de anúncios em um feed organizado por localização e categoria.  
- Opção de marcar um item como "Vendido" para evitar anúncios inativos.  

### 🔧 Tecnologias sugeridas:  
Firebase Firestore, PostgreSQL/MongoDB (armazenamento), Cloudinary/Firebase Storage (imagens).  

---

## ✅ 3. Filtros de Localização Inteligente  
🔹 **Objetivo:** Permitir que os usuários encontrem produtos e serviços próximos a eles.  

### 📌 Funcionalidades:  
- Seleção manual da área de interesse (meu condomínio, bairros próximos, universidades, etc.).  
- Filtragem por distância (ex.: até 2km, até 5km).  
- Opção de buscar apenas dentro do condomínio do usuário.  

### 🔧 Tecnologias sugeridas:  
Google Maps API, GeoFire (para busca geolocalizada).  

---

## ✅ 4. Chat Interno entre Usuários  
🔹 **Objetivo:** Facilitar a comunicação entre compradores e vendedores diretamente no app.  

### 📌 Funcionalidades:  
- Mensagens privadas entre usuários.  
- Notificações push para novas mensagens.  
- Indicação de mensagens lidas/não lidas.  

### 🔧 Tecnologias sugeridas:  
Firebase Firestore (mensagens em tempo real), Firebase Cloud Messaging (notificações push).  

---

## ✅ 5. Moderação e Segurança  
🔹 **Objetivo:** Criar um ambiente seguro e confiável para os usuários.  

### 📌 Funcionalidades:  
- **Sistema de Denúncias:** Opção para reportar anúncios ou usuários suspeitos.  
- **Regras básicas:** Termos de uso visíveis e aceitos no cadastro.  
- **Bloqueio de usuários:** Moderadores podem suspender perfis problemáticos.  

### 🔧 Tecnologias sugeridas:  
Firebase Moderation, sistema interno de denúncias para moderação manual.  

---

# Plano de Assinatura no MVP  

## ✅ 1. Modelo de Assinatura  

### **Usuário Gratuito:**  
- Pode postar até **3 anúncios simultâneos**.  
- Cada anúncio pode conter no máximo **2 imagens**.  
- Acesso ao marketplace e chat normalmente.  

### **Usuário Premium (Pago):**  
- **Anúncios ilimitados**.  
- Pode adicionar **mais de 2 imagens** por anúncio.  
- Possibilidade de **destacar anúncios gratuitamente** (X vezes por mês).  
- **Prioridade no suporte** e futuras funcionalidades exclusivas.  

---

## ✅ 2. Implementação da Assinatura  

### 📌 Funcionalidades:  
- Tela de assinatura com detalhes dos benefícios.  
- Sistema de pagamento integrado (**Stripe, Mercado Pago ou App Store/Google Play**).  
- Controle de planos no perfil do usuário.  
- Alerta quando o usuário gratuito atingir o limite de anúncios ou imagens.  

### 🔧 Tecnologias sugeridas:  
- **Stripe / Mercado Pago** (pagamentos recorrentes).  
- **Firebase Firestore** para armazenar o status da assinatura.  
- **Cloud Functions** para gerenciar permissões de usuários pagos/gratuitos.  

---

## ✅ 3. Experiência do Usuário  
- **Ao tentar criar um 4º anúncio**, um pop-up oferece o upgrade para o plano premium.  
- **Ao tentar adicionar mais de 2 imagens**, uma mensagem alerta sobre a limitação.  
- **Página de “Meus Anúncios”** mostrando a contagem de anúncios ativos.  

