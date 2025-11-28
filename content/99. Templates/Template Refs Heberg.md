---
Type (icon): hotel
Adresse: 2425 Rue de Cholet 49400 Distré
Tel: 02.41.40.25.95
Email: reception@domainedepresle.fr
Site: www.domainedepresle.fr
Prix:
  - 88€
  - 114€
Services:
  - Parking privé
  - Piscine
Payements:
  - Cheque-vacances
  - Ticket-restau
Chambres: 21
Ouvertures: Du 01/01 au 31/12
Ville: Distré
Autre Infos: Petit dej à 14€
Coordinates:
colorIcon: "#d413d4"
---

> [!<% tp.frontmatter.Type %>] <% tp.file.title %>
> Type: <% tp.frontmatter.Type %>
> 
> Adresse: <% tp.frontmatter["Adresse"] %>
> Tel: <% tp.frontmatter.Tel %>
> Email: <% tp.frontmatter.Email %>
> Site: <% tp.frontmatter.Site %>
> 
> Prix:
> <% tp.frontmatter.Prix.map(prop => ` - "${prop}"`).join("\n >") %>
> 
> Services:
> <% tp.frontmatter.Services.map(prop => ` - "${prop}"`).join("\n >") %>
>
> Payements:
> <% tp.frontmatter.Payements.map(prop => ` - "${prop}"`).join("\n >") %>
>
> Chambres: <% tp.frontmatter.Chambres %>
> Ouvertures: <% tp.frontmatter["Ouvertures"] %>
> Ville: <% tp.frontmatter.Ville %>
> Autres: <% tp.frontmatter["Autre Infos"] %>


