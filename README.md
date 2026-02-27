# mielectric-open

Página de redirecionamento para abrir o app via deep link `mielectric://`.

## URL pública (GitHub Pages)

Após remover o domínio customizado, a URL padrão do Pages é:

https://ramonmirandaa-crypto.github.io/mielectric-open/

## URL para botão no Salesforce

Use esta URL no botão/link (objeto `Opportunity`):

https://ramonmirandaa-crypto.github.io/mielectric-open/?recordId={!Opportunity.Proposta__c}&cliente={!URLENCODE(Opportunity.Nome_da_Conta__c)}&Nomeresponsavel={!URLENCODE(Opportunity.Nome_do_contato__c)}&email={!URLENCODE(Opportunity.Email_do_Contato__c)}

## Observações

- O parâmetro deve permanecer com o nome exato `Nomeresponsavel`.
- A página converte os parâmetros recebidos para `mielectric://novo?...`.
