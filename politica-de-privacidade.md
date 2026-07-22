# Política de Privacidade — Fluente

**Última atualização:** 21 de julho de 2026  
**Aplicativo:** Fluente — Aprenda Idiomas  
**Pacote:** com.fluente.app  
**Desenvolvedor:** Vando Maciel  
**Contato:** [SEU EMAIL AQUI]

---

## 1. Introdução

Bem-vindo ao **Fluente**. Esta Política de Privacidade descreve como coletamos, usamos, armazenamos e protegemos as informações dos nossos usuários. Ao utilizar o aplicativo, você concorda com os termos descritos neste documento.

---

## 2. Dados Coletados

### 2.1 Dados de Conta
Para criar e gerenciar sua conta, coletamos:
- **Endereço de e-mail** (usado como identificador de login)
- **Senha** (armazenada de forma criptografada pelo Supabase)
- **Data de criação da conta**

### 2.2 Dados de Uso e Progresso
Para personalizar sua experiência de aprendizado, registramos:
- Histórias e etapas de leitura concluídas
- Lições e fases da Trilha completadas
- Missões de pronúncia realizadas
- Palavras tocadas e consultadas no dicionário
- Sequência de dias de estudo (streak) e XP acumulado
- Erros de pronúncia para o sistema de revisão inteligente

### 2.3 Dados de Voz (Microfone)
O aplicativo solicita acesso ao **microfone** exclusivamente para:
- Avaliação de pronúncia nas atividades de "Falar"
- Conversação com o tutor de IA
- Ditado nas atividades de escuta

> ⚠️ **Importante:** As gravações de voz são processadas localmente no dispositivo via API de reconhecimento de fala nativa do Android/iOS. Nenhum áudio é armazenado em nossos servidores. O processamento é feito em tempo real e descartado imediatamente após a avaliação.

### 2.4 Dados de Assinatura
Se você adquirir um plano pago, coletamos:
- Plano contratado e status da assinatura
- Minutos de IA utilizados no período
- Data de renovação do plano

O processamento de pagamentos é realizado por plataforma terceira segura. Não armazenamos dados de cartão de crédito.

### 2.5 Dados Técnicos (Automáticos)
Coletamos automaticamente:
- Identificador único do dispositivo (para controle de sessão)
- Sistema operacional e versão do aplicativo
- Idioma configurado no dispositivo

---

## 3. Como Usamos os Dados

Utilizamos suas informações para:

| Finalidade | Base Legal |
|---|---|
| Criar e autenticar sua conta | Execução de contrato |
| Salvar e sincronizar seu progresso | Execução de contrato |
| Personalizar o conteúdo de aprendizado | Interesse legítimo |
| Avaliar sua pronúncia em tempo real | Consentimento (permissão de microfone) |
| Gerenciar sua assinatura | Execução de contrato |
| Melhorar o aplicativo com base em dados de uso | Interesse legítimo |
| Enviar notificações de lembrete de estudo (se ativadas) | Consentimento |

---

## 4. Compartilhamento de Dados

**Não vendemos seus dados pessoais.** Compartilhamos informações apenas com os seguintes parceiros técnicos, estritamente necessários para o funcionamento do app:

| Parceiro | Finalidade | Política de Privacidade |
|---|---|---|
| **Supabase** | Banco de dados, autenticação e armazenamento de progresso | [supabase.com/privacy](https://supabase.com/privacy) |
| **ElevenLabs** | Síntese de voz para o tutor de IA | [elevenlabs.io/privacy](https://elevenlabs.io/privacy) |
| **Google (TTS/STT)** | Reconhecimento de fala nativo do Android | [policies.google.com/privacy](https://policies.google.com/privacy) |
| **Apple (TTS/STT)** | Reconhecimento de fala nativo do iOS | [apple.com/privacy](https://www.apple.com/privacy/) |

Todos os parceiros operam em conformidade com o GDPR e a LGPD.

---

## 5. Armazenamento e Segurança

- Os dados são armazenados em servidores da **Supabase** com criptografia em trânsito (TLS) e em repouso
- As senhas são armazenadas com hash bcrypt — nunca em texto plano
- O acesso aos dados é restrito por autenticação JWT com tokens de curta duração
- Realizamos revisões periódicas de segurança

---

## 6. Retenção de Dados

| Tipo de dado | Período de retenção |
|---|---|
| Dados de conta e progresso | Enquanto a conta estiver ativa |
| Logs de uso | 12 meses |
| Dados de voz | Não armazenados (processamento em tempo real) |
| Dados após exclusão de conta | Excluídos em até 30 dias |

---

## 7. Seus Direitos (LGPD / GDPR)

Você tem direito a:

- **Acesso:** solicitar uma cópia dos seus dados
- **Correção:** atualizar dados incorretos
- **Exclusão:** solicitar a exclusão da sua conta e todos os dados associados
- **Portabilidade:** receber seus dados em formato estruturado
- **Oposição:** opor-se ao processamento para fins de marketing
- **Revogação de consentimento:** retirar permissões concedidas (ex: microfone, notificações)

Para exercer qualquer direito, entre em contato: **[SEU EMAIL AQUI]**

---

## 8. Permissões do Aplicativo

| Permissão | Motivo |
|---|---|
| `RECORD_AUDIO` | Avaliação de pronúncia e conversação com IA |
| `INTERNET` | Sincronização de progresso e acesso ao tutor de IA |
| `MODIFY_AUDIO_SETTINGS` | Ajuste de volume durante reprodução de áudio |
| `FOREGROUND_SERVICE` | Reprodução de áudio em segundo plano (músicas) |
| `FOREGROUND_SERVICE_MEDIA_PLAYBACK` | Continuidade da reprodução com tela bloqueada |

---

## 9. Privacidade de Crianças

O Fluente é destinado a usuários com **13 anos ou mais**. Não coletamos intencionalmente dados de menores de 13 anos. Caso identifiquemos que uma conta foi criada por uma criança abaixo dessa idade, a conta será excluída.

---

## 10. Alterações nesta Política

Reservamos o direito de atualizar esta Política de Privacidade. Em caso de mudanças significativas, notificaremos os usuários por:
- Notificação dentro do aplicativo
- E-mail cadastrado

A data da última atualização está sempre indicada no topo deste documento.

---

## 11. Contato

Para dúvidas, solicitações ou exercício de direitos:

**Desenvolvedor:** Vando Maciel  
**E-mail:** [SEU EMAIL AQUI]  
**País:** Brasil  

---

*Esta política foi elaborada em conformidade com a Lei Geral de Proteção de Dados (LGPD — Lei nº 13.709/2018) e o Regulamento Geral de Proteção de Dados da União Europeia (GDPR).*
