# id-acess-lab
Resumo simples para o bootcamp Azure Essentials

	Ø Identidade, Segurança e Acesso
		○ Microsoft Entra ID
			§ O Microsoft Entra ID é o serviço de gerenciamento de identidades e acesso baseado em nuvem do Microsoft Azure.
				□ Autenticação (os funcionários entram para acessar os recursos).
				□ Logon único (SSO).
				□ Gerenciamento de aplicativos.
				□ Negócios para Negócios (B2B).
				□ Gerenciamento de dispositivos.
			§ Microsoft Entra Domain Services
				□ Benefícios dos serviços de domínio baseados em nuvem sem gerenciar os controladores de domínio
				□ Execute aplicativos herdados (que não podem utilizar os padrões de autenticação modernos) na nuvem.
				□ Sincronizar automaticamente a partir do Microsoft Entra ID
		○ Autenticação e Autorização
			§ Identifica a pessoa ou serviços buscando acesso a um recurso
			§ Solicita credenciais de acesso legítimo
			§ Base para criar princípios de identidade e controle de acesso seguros
			§ Autenticação Multifator
				□ Fornece segurança adicional para as identidade, exigindo dois ou mais elementos para autenticação completa.

			• Acesso Condicional
				□ Associação de usuário ou grupo
				□ Local do IP
				□ Dispositivo
				□ Aplicativo
				□ Detecção de Risco
				□ Controle de acesso baseado em função
					® Gerenciamento de acesso de granularidade fina.
					® Divida as tarefas dentro da equipe e conceda somente a quantidade de acesso de que os usuários precisam para trabalhar. (RBAC)
					® Habilite o acesso ao portal do Azure e os controle de acesso aos recursos.				
					® Uma abordagem em camadas para proteger sistemas de computador
					® Fornece vários níveis de proteção.
					® Ataques contra uma camada são isolados das camadas subsequentes
				□ Defender for Cloud
					® O Microsoft Defender for Cloud é um serviço de monitoramento que fornece proteção contra ameaças nos datacenters do Azure e locais.
					® Fornece recomendações de segurança.
					® Detecta e bloqueia malwares
					® Analisa e identifica ataques potenciais
					® Controle de acesso just-in-time para portas.
