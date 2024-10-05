# Gerenciamento de Políticas e Acessos no Azure

Este laboratório explorou as funcionalidades de **Locks**, **Microsoft Purview** e **Policy** no Azure, fornecendo uma visão sobre como gerenciar o acesso e as políticas de segurança na nuvem.

## Tópicos explorados:

### 1. **Locks (Bloqueios)**
Os **Locks** no Azure ajudam a proteger recursos de alterações acidentais ou exclusões. Existem dois tipos principais de bloqueios:
   - **CanNotDelete** (Exclusão não permitida): Os usuários podem modificar o recurso, mas não podem deletá-lo.
   - **ReadOnly** (Somente leitura): Os usuários podem visualizar os recursos, mas não podem modificá-los.

#### Exemplo: Bloqueio de Delete
No laboratório, configuramos um bloqueio do tipo **CanNotDelete** em um recurso, garantindo que ele não seja excluído acidentalmente. Este bloqueio é útil para proteger recursos críticos de mudanças não intencionais.

### 2. **Microsoft Purview**
O **Microsoft Purview** é uma suíte completa de soluções para governança de dados, gerenciamento de informações e conformidade, sendo essencial para a administração e segurança de dados.

#### Componentes do Microsoft Purview:
   - **Data Map**: Mapeia os dados armazenados na organização, permitindo a descoberta e classificação de informações.
   - **Data Catalog**: Um catálogo centralizado que ajuda a organizar, acessar e gerenciar dados.
   - **Information Protection**: Ferramenta para classificar e proteger documentos e e-mails, baseada em políticas definidas pela organização.
   - **Audit**: Monitora e rastreia atividades em sua infraestrutura de dados, garantindo auditorias confiáveis.
   - **Risk & Compliance**: Gerenciamento de riscos e conformidade com regulamentações, como **GDPR** e **LGPD**.
   - **Microsoft Priva**: Oferece soluções para gerenciamento de privacidade, ajudando as organizações a cumprir com as normas da **LGPD** e outras leis de proteção de dados.
   - **Data Security**: Conjunto de ferramentas que garante a segurança de dados sensíveis, fornecendo visibilidade e controle sobre quem acessa os dados.

### 3. **Policy (Política de Acesso)**
As **Azure Policies** garantem que os recursos sejam criados e gerenciados de acordo com os padrões de conformidade da organização. No laboratório, utilizamos políticas para restringir a criação de recursos em localizações específicas.

#### Exemplo: Allowed Locations
Configuramos uma política de **Allowed Locations** para restringir onde os recursos podem ser criados. Esta política impede que usuários criem recursos fora das regiões aprovadas, o que ajuda a gerenciar conformidade geográfica e otimizar custos.

---

Este laboratório forneceu uma base sólida para entender como gerenciar políticas de segurança e conformidade no Azure, com foco em garantir a integridade dos recursos e a proteção dos dados.
