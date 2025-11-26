---
Type: Hotel
Adresse: 5-7 Place des Plantagenets 49590
Tel: 02.41.51.71.11
Email: info@lacroixblanche.fr
Site: www.lacroixblanche.fr
Prix:
  - 79€
  - 200€
Services:
  - Parking privé
  - Petit-dej 🥐
  - Restau 🍴
  - Terrasse
  - Location de vélo 🚲
  - Piscine
Payements:
  - Cheque-vacances
Chambres: 24
Ouvertures: Du 1 Fév au 23 Déc
Ville: Fontevraud
Autre Infos:
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


