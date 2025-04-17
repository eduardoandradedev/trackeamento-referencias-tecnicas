# Documentação de Referência para Marketing Digital

Este documento centraliza as principais referências técnicas para implementação e configuração de ferramentas de rastreamento de marketing digital, especialmente para e-commerce. Use este arquivo como referência em consultas técnicas para desenvolvimento, análise e otimização de campanhas.

## Google Ads

### Conversões e Rastreamento

1. **[Opções de acompanhamento de conversões](https://support.google.com/google-ads/answer/1722054)**
   - Visão geral dos métodos de rastreamento disponíveis
   - Comparação entre diferentes tipos de conversão
   - Requisitos de implementação
   - Recomendações por tipo de negócio

2. **[Configurar o acompanhamento de conversões do site](https://support.google.com/tagmanager/answer/6106009?sjid=2661726098372043519-SA))**
   - Implementação passo a passo
   - Opções de tag: global site tag vs. GTM
   - Verificação e solução de problemas
   - Melhores práticas para diferentes setores

3. **[Eventos e parâmetros de remarketing dinâmico do Google Ads](https://support.google.com/google-ads/answer/7305793)**
   - Parâmetros obrigatórios para remarketing dinâmico
   - Estrutura de dados para diferentes tipos de eventos
   - Integração com feed de produtos
   - Implementação e verificação

4. **[Remarketing padrão do Google Ads](https://support.google.com/tagmanager/answer/6106960)**
   - Implementação via Google Tag Manager
   - Configuração de listas de público
   - Requisitos de dados para produtos
   - Segmentação avançada

### Conversões Otimizadas

5. **[Configurar as conversões otimizadas para a Web usando o GTM](https://support.google.com/google-ads/answer/13262500)**
   - Encontrar variáveis das conversões otimizadas
   - Ativar as conversões otimizadas na tag do GTM
   - Configurar conversões otimizadas manuais padrão
   - Identificar e definir variáveis de conversões otimizadas

6. **[Ferramenta de assistência de conversões otimizadas](https://support.google.com/google-ads/answer/15299126)**
   - Funcionalidades disponíveis
   - Configuração e implementação
   - Diagnóstico de problemas comuns
   - Análise de desempenho

### Privacidade e Consentimento

7. **[Compatibilidade com o modo de consentimento do GTM](https://support.google.com/tagmanager/answer/10718549/?hl=pt-BR)**
   - Implementação de consentimento para Google Ads
   - Configuração por região geográfica
   - Integração com CMPs (Consent Management Platforms)
   - Verificação de conformidade

## Google Tag Manager (GTM)

### Fundamentos e Configuração

1. **[Sobre a tag do Google](https://support.google.com/tagmanager/answer/11994839?hl=pt-BR)**
   - Visão geral da tag do Google e sua integração com o ecossistema
   - Principais elementos e diferenças em relação ao GTM tradicional
   - Benefícios da implementação unificada

2. **[Encontrar o ID da tag do Google](https://support.google.com/tagmanager/answer/15107467?hl=pt-BR)**
   - Como localizar IDs de tag em diferentes plataformas:
     - Google Ads
     - Google Analytics
     - Campaign Manager
     - Google Tag Manager
   - Resolução de problemas comuns com IDs

3. **[Definir as configurações da tag do Google](https://support.google.com/tagmanager/answer/12131703?hl=pt-BR)**
   - Configurações avançadas para personalização
   - Opções de consent mode e privacidade
   - Definições específicas por plataforma
   - Otimização de desempenho

### Implementações Avançadas

4. **[Custom Templates Guide For Google Tag Manager](https://www.simoahava.com/analytics/custom-templates-guide-for-google-tag-manager/)**
   - Criação de modelos personalizados
   - Melhores práticas de desenvolvimento
   - Casos de uso e exemplos práticos
   - Limitações e soluções

5. **[Blog Simo Ahava](https://www.simoahava.com/)**
   - Recurso técnico avançado por especialista reconhecido
   - Tutoriais detalhados sobre implementações complexas
   - Análises de recursos novos e experimentais
   - Solução de problemas específicos

### Server-Side e Desenvolvimento

6. **[APIs de inclusão de tags no servidor](https://developers.google.com/tag-platform/tag-manager/server-side/api?hl=pt-br)**
   - Implementação server-side completa
   - Documentação de APIs para desenvolvimento
   - Integração com outras plataformas
   - Segurança e conformidade de dados

7. **[JavaScript Sandbox](https://developers.google.com/tag-platform/tag-manager/templates/sandboxed-javascript?hl=pt-br)**
   - Limitações do ambiente sandbox
   - APIs disponíveis para desenvolvedores
   - Métodos seguros para manipulação de dados
   - Testes e depuração

8. **[Reutilizar as definições de configuração no GTM](https://support.google.com/tagmanager/answer/13438166)**
   - Técnicas para reutilização de código
   - Configurações compartilhadas
   - Otimização de containers
   - Gestão de implementações em grande escala

## Google Analytics 4 (GA4)

### Implementação e Eventos

1. **[Eventos recomendados](https://developers.google.com/analytics/devguides/collection/ga4/reference/events?hl=pt-br&client_type=gtag)**
   - Lista completa de eventos padronizados
   - Parâmetros requeridos e opcionais
   - Implementação via gtag.js
   - Casos de uso específicos

2. **[Eventos de medição otimizada](https://support.google.com/analytics/answer/9216061)**
   - Coleta automática de eventos
   - Configuração e personalização
   - Limitações e alternativas
   - Verificação de implementação

3. **[Medir o e-commerce](https://developers.google.com/analytics/devguides/collection/ga4/ecommerce?client_type=gtm&hl=pt-br)**
   - Implementação completa para e-commerce
   - Eventos de funil de compra
   - Parâmetros de produtos e transações
   - Integração com GTM
   - Validação e troubleshooting

## Meta Ads (Facebook)

### Pixel e Rastreamento Básico

1. **[Eventos-padrão](https://developers.facebook.com/docs/meta-pixel/reference)**
   - Eventos oficiais reconhecidos pela plataforma
   - Parâmetros e formato de dados
   - Implementação via JavaScript
   - Verificação e depuração

2. **[Rastreamento de conversão](https://developers.facebook.com/docs/meta-pixel/implementation/conversion-tracking)**
   - Configuração de eventos de conversão
   - Otimização de campanhas
   - Janelas de atribuição
   - Verificação de implementação

3. **[Parâmetros de informações do cliente](https://developers.facebook.com/docs/marketing-api/conversions-api/parameters/customer-information-parameters)**
   - Opções de hashing de dados
   - Campos obrigatórios e opcionais
   - Práticas recomendadas de privacidade
   - Taxas de correspondência

4. **[Eventos e parâmetros obrigatórios para anúncios de catálogo Advantage+](https://pt-br.facebook.com/business/help/606577526529702?id=1205376682832142)**
   - Requisitos específicos para campanhas de catálogo
   - Mapeamento de parâmetros de produto
   - Otimização de feed de produtos
   - Solução de problemas comuns

### Conversions API (CAPI)

5. **[API de Conversões](https://developers.facebook.com/docs/marketing-api/conversions-api)**
   - Visão geral e benefícios
   - Comparação com Pixel
   - Requisitos de implementação
   - Casos de uso recomendados

6. **[Parâmetros-padrão](https://developers.facebook.com/docs/marketing-api/conversions-api/parameters/custom-data)**
   - Estrutura de dados esperada
   - Campos obrigatórios
   - Otimização de dados enviados
   - Validação de implementação

7. **[API de Conversões - Parâmetros completos](https://developers.facebook.com/docs/marketing-api/conversions-api/parameters)**
   - Documentação abrangente de todos os parâmetros
   - Requisitos de formato
   - Opções avançadas
   - Solução de problemas

8. **[API de Conversões para o GTM Server-Side](https://developers.facebook.com/docs/marketing-api/conversions-api/guides/gtm-server-side)**
   - Implementação via GTM server-side
   - Templates disponíveis
   - Configuração de clientes
   - Validação e depuração

9. **[API de Conversões Offline](https://developers.facebook.com/docs/marketing-api/offline-conversions/)**
   - Importação de dados offline
   - Requisitos de formato
   - Correspondência com público online
   - Atribuição de campanhas

## Como usar esta documentação em consultas

Ao fazer perguntas relacionadas a estas plataformas, você pode referenciar este documento de várias maneiras:

### Exemplos de consultas específicas:

1. **Para implementação de e-commerce no GA4:**
   ```
   "Com base na documentação de referência de GA4 para e-commerce, como devo estruturar o evento de 'add_to_cart' para incluir informações de variantes de produto?"
   ```

2. **Para configuração avançada do GTM:**
   ```
   "Consultando a documentação do JavaScript Sandbox do GTM, quais APIs posso usar para acessar informações de cookies de terceiros de forma segura?"
   ```

3. **Para implementação da Meta Conversions API:**
   ```
   "De acordo com a documentação da API de Conversões da Meta, qual é a melhor forma de implementar o evento 'Purchase' via servidor para maximizar a correspondência com o Pixel?"
   ```

4. **Para remarketing dinâmico do Google Ads:**
   ```
   "Consultando a documentação de 'Eventos e parâmetros de remarketing dinâmico do Google Ads', quais são os parâmetros obrigatórios para implementar o remarketing dinâmico em um e-commerce de moda?"
   ```

### Perguntas sobre integração entre plataformas:

```
"Como posso implementar o rastreamento de conversões da Meta via GTM Server-Side, conforme as documentações de ambas as plataformas que compartilhei?"
```

---

**Nota:** Esta documentação é atualizada regularmente. Última revisão: Abril 2025.
