---
title: Fazer downgrade da sua assinatura do GitHub
intro: 'Você pode fazer o downgrade da assinatura para qualquer tipo de conta em {% data variables.product.product_location %} a qualquer momento.'
redirect_from:
  - /github/setting-up-and-managing-billing-and-payments-on-github/downgrading-your-github-subscription
  - /articles/downgrading-your-personal-account-s-billing-plan
  - /articles/how-do-i-cancel-my-account
  - /articles/downgrading-a-user-account-to-free
  - /articles/removing-paid-seats-from-your-organization
  - /articles/downgrading-your-organization-s-paid-seats
  - /articles/downgrading-your-organization-s-billing-plan
  - /articles/downgrading-an-organization-with-per-seat-pricing-to-free
  - /articles/downgrading-an-organization-with-per-repository-pricing-to-free
  - /articles/downgrading-your-organization-to-free
  - /articles/downgrading-your-organization-from-the-business-plan-to-the-team-plan
  - /articles/downgrading-your-organization-from-github-business-cloud-to-the-team-plan
  - /articles/downgrading-your-github-billing-plan
  - /articles/downgrading-your-github-subscription
  - /github/setting-up-and-managing-billing-and-payments-on-github/managing-billing-for-your-github-account/downgrading-your-github-subscription
versions:
  fpt: '*'
  ghec: '*'
topics:
  - Accounts
  - Downgrades
  - Organizations
  - Repositories
  - User account
shortTitle: Downgrade da assinatura
---

## Rebaixando sua assinatura {% data variables.product.product_name %}

When you downgrade your personal account or organization's subscription, pricing and account feature changes take effect on your next billing date. Changes to your paid personal account or organization subscription does not affect subscriptions or payments for other paid {% data variables.product.prodname_dotcom %} features. Para obter mais informações, consulte "[Como a atualização ou o downgrade afeta o processo de cobrança?](/articles/how-does-upgrading-or-downgrading-affect-the-billing-process)."

## Downgrading your personal account's subscription

If you downgrade your personal account from {% data variables.product.prodname_pro %} to {% data variables.product.prodname_free_user %}, the account will lose access to advanced code review tools on private repositories. {% data reusables.gated-features.more-info %}

{% data reusables.user-settings.access_settings %}
{% data reusables.user-settings.billing_plans %}
1. Em "Plano atual", use o menu suspenso **Editar** e clique em **Fazer downgrade para grátis**. ![Botão Downgrade to free (Fazer downgrade para o Free)](/assets/images/help/billing/downgrade-to-free.png)
5. Read the information about the features your personal account will no longer have access to on your next billing date, then click **I understand. Continue com o downgrade**. ![Continuar com o botão de downgrade](/assets/images/help/billing/continue-with-downgrade.png)

Se você tiver publicado um site do {% data variables.product.prodname_pages %} em um repositório privado e adicionado um domínio personalizado, remova ou atualize seus registros DNS antes de fazer downgrade do {% data variables.product.prodname_pro %} para {% data variables.product.prodname_free_user %}, a fim de evitar o risco de uma aquisição de domínio. Para obter mais informações, consulte "[Gerenciar um domínio personalizado para seu site do {% data variables.product.prodname_pages %}](/articles/managing-a-custom-domain-for-your-github-pages-site)".

## Rebaixando a assinatura da sua organização

{% data reusables.dotcom_billing.org-billing-perms %}

Se você fizer o downgrade da sua organização de {% data variables.product.prodname_team %} para {% data variables.product.prodname_free_team %}, para uma organização, a conta perderá o acesso a ferramentas avançadas de colaboração e gerenciamento para equipes.

Se você fizer o downgrade da sua organização de {% data variables.product.prodname_ghe_cloud %} para {% data variables.product.prodname_team %} ou {% data variables.product.prodname_free_team %}, a conta perderá o acesso a controles avançados de segurança, conformidade e implantação. {% data reusables.gated-features.more-info %}


{% note %}

**Nota:** Se você estiver testando {% data variables.product.prodname_ghe_cloud %} no momento e você não comprar {% data variables.product.prodname_enterprise %} antes do término do teste, sua organização será automaticamente rebaixada para {% data variables.product.prodname_free_team %} ou {% data variables.product.prodname_team %}. Para obter mais informações, consulte "[Configurar uma versão de avaliação do {% data variables.product.prodname_ghe_cloud %}](/get-started/signing-up-for-github/setting-up-a-trial-of-github-enterprise-cloud#finishing-your-trial)".

{% endnote %}

{% data reusables.organizations.billing-settings %}
1. Em "Plano atual", use o menu suspenso **Editar** e clique na opção de downgrade que você deseja. ![Botão Downgrade (Fazer downgrade)](/assets/images/help/billing/downgrade-option-button.png)
{% data reusables.dotcom_billing.confirm_cancel_org_plan %}

## Fazer downgrade da assinatura de uma organização com o preço antigo por repositório

{% data reusables.dotcom_billing.org-billing-perms %}

{% data reusables.dotcom_billing.switch-legacy-billing %} Para obter mais informações, consulte "[Mudar sua organização de um preço por repositório para um preço por usuário](/billing/managing-billing-for-your-github-account/upgrading-your-github-subscription#switching-your-organization-from-per-repository-to-per-user-pricing)".

{% data reusables.organizations.billing-settings %}
5. Em "Assinaturas", selecione o menu suspenso "Editar" e clique em **Editar plano**. ![Menu suspenso Editar plano](/assets/images/help/billing/edit-plan-dropdown.png)
1. Em "Billing/Plans" (Cobrança/Planos), ao lado do plano que deseja alterar, clique em **Downgrade**. ![Botão Downgrade (Fazer downgrade)](/assets/images/help/billing/downgrade-plan-option-button.png)
1. Insira o motivo pelo qual você está fazendo o downgrade da sua conta e clique em **Fazer downgrade do plano**. ![Caixa de texto para motivo de downgrade e botão de downgrade](/assets/images/help/billing/downgrade-plan-button.png)

## Remover estações pagas da sua organização

Para reduzir o número de estações pagas usadas pela sua organização, remova integrantes dela ou converta integrantes em colaboradores externos e conceda a eles acesso somente a repositórios públicos. Para obter mais informações, consulte:
- "[Remover um integrante da organização](/articles/removing-a-member-from-your-organization)"
- "[Converter um integrante da organização em colaborador externo](/articles/converting-an-organization-member-to-an-outside-collaborator)"
- "[Gerenciar o acesso de um indivíduo a um repositório da organização](/articles/managing-an-individual-s-access-to-an-organization-repository)"

{% data reusables.organizations.billing-settings %}
1. Em "Plano atual", use o menu suspenso **Editar** e clique em **Remover estações**. ![menu suspenso para remover estações](/assets/images/help/billing/remove-seats-dropdown.png)
1. Em "Remove seats" (Remover estações), selecione o número de estações em que você deseja fazer downgrade. ![opção de remover estações](/assets/images/help/billing/remove-seats-amount.png)
1. Revise as informações sobre seu novo pagamento na sua próxima data de cobrança e clique em **Remove seats** (Remover estações). ![botão de remover estações](/assets/images/help/billing/remove-seats-button.png)

## Leia mais

- "[Produtos do {% data variables.product.prodname_dotcom %}](/articles/github-s-products)"
- "[Como a atualização ou o downgrade afetam o processo de cobrança?](/articles/how-does-upgrading-or-downgrading-affect-the-billing-process)"
- "[Sobre a cobrança no {% data variables.product.prodname_dotcom %}](/articles/about-billing-on-github)"
- "[Sobre preços por usuário](/articles/about-per-user-pricing)"
