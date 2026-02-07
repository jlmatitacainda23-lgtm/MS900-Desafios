# Desafio 6 – Gestão do Ciclo de Vida LearnIT

Este diretório documenta o processo de desativação de conta (*offboarding*) do utilizador **João Miguel Costa**, demonstrando as boas práticas de segurança e conformidade no Microsoft 365.

##  Procedimento Técnico Executado

Para garantir a proteção dos dados e a gestão eficiente dos recursos, foram realizadas as seguintes etapas:

1. **Bloqueio de Sessão**: Suspensão imediata do início de sessão para impedir o acesso a e-mails e ficheiros da organização.
2. **Eliminação de Utilizador**: Remoção da identidade da lista de utilizadores ativos e libertação automática das licenças associadas para reutilização.
3. **Validação de Retenção**: Verificação da conta no diretório de utilizadores eliminados, onde o sistema garante a possibilidade de restauro total num período de carência de 30 dias.

##  Evidências do Processo

* **`bloqueio-login.png`**: Demonstra o utilizador com o estado "Início de sessão bloqueado" a vermelho no portal.
* **`confirmacao-eliminacao.png`**: Captura de ecrã da mensagem de sucesso do sistema após o comando de eliminação.
* **`utilizador-eliminado-lista.png`**: Comprovação de que o utilizador se encontra na área de "Utilizadores eliminados" para fins de conformidade.
