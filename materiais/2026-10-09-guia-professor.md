# Guia do professor — 09/10/2026 — Servidores · 1º A · CEPEF
**Estado: PLANEJADO / MATERIAL PRODUZIDO; não ministrado sem confirmação.**
## Objetivo
Aproveitar o 6º tempo como prática complementar de Servidores com Radmin VPN previamente instalado. Aplicar servidor/cliente, pasta compartilhada SMB, permissões de leitura, diagnóstico e evidências. **Não confundir o SMB do Windows com instalação de Samba ou configuração de NFS Linux.**
## Preparação do professor
1. Confirmar autorização e política de TI para compartilhamento SMB na rede virtual.
2. Criar C:\Servidor_Aula com três documentos fictícios; não usar arquivos pessoais.
3. Criar e utilizar conta/grupo de acesso didático autorizado; limitar compartilhamento e NTFS a leitura.
4. Testar previamente UNC \\IP_VPN_DO_PROFESSOR\Servidor_Aula em uma máquina cliente; verificar firewall sem desativá-lo.
5. Se houver bloqueio institucional, aplicar plano B demonstrativo e registrar a limitação.
## Cronograma
0–8 VPN/IP; 8–18 configurar serviço; 18–30 clientes; 30–40 diagnóstico; 40–50 ficha/quiz.
## Evidências e critérios
- Identifica papéis servidor e cliente (2 pontos)
- Distingue VPN de SMB (2 pontos)
- Realiza ou diagnostica acesso com evidência (3 pontos)
- Explica permissão de leitura e segurança (2 pontos)
- Documenta procedimento e problema encontrado (1 ponto)
## Gabarito
Servidor: computador do professor. Protocolo: SMB. Radmin cria conectividade virtual, SMB compartilha arquivos. Leitura permite abrir/copiar, não editar no servidor. Samba fornece compatibilidade com SMB em Linux/Windows, mas sua instalação não foi praticada nesta aula.
## Continuidade
Retomar prática NFS/Samba Linux em aula própria, após confirmação do conteúdo efetivamente executado em 08/10 e 09/10. Não marcar automaticamente aula como ministrada.
