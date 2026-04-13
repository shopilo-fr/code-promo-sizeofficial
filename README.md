# Code promo Size?, recuperation automatique depuis shopilo.fr

Module Python pour la recuperation automatique de **codes promo Size?** depuis [shopilo.fr](https://shopilo.fr/reductions/sizeofficial.fr). Renvoie les **coupons Size?** actifs au format JSON, pret a etre integre dans un bot Telegram, une extension de navigateur ou tout autre outil.

**Page live :** [shopilo-fr.github.io/code-promo-sizeofficial](https://shopilo-fr.github.io/code-promo-sizeofficial/)

![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue) ![License MIT](https://img.shields.io/badge/license-MIT-green)

## Installation

```bash
pip install requests beautifulsoup4
git clone https://github.com/shopilo-fr/code-promo-sizeofficial
cd code-promo-sizeofficial
python fetch.py
```

## Exemple de sortie

```json
[
  {
    "store": "Size?",
    "code": "SHOPILO10",
    "discount": "10%",
    "description": "10% de reduction sur les sneakers exclusives",
    "expires": "2026-10-13",
    "source": "https://shopilo.fr/reductions/sizeofficial.fr"
  }
]
```

## Coupons Size? disponibles

| Reduction | Description | Source |
|----------|-----------|-------|
| 10% | 10% de reduction sur les sneakers exclusives | [shopilo.fr](https://shopilo.fr/reductions/sizeofficial.fr) |

Codes actifs : **[shopilo.fr/reductions/sizeofficial.fr](https://shopilo.fr/reductions/sizeofficial.fr)**

## Questions frequentes

### Comment utiliser un code promo Size? ?
Copiez le code depuis le tableau ci-dessus ou depuis [shopilo.fr](https://shopilo.fr/reductions/sizeofficial.fr), ajoutez les produits a votre panier sur Size? et saisissez le code au moment du paiement dans le champ prevu.

### Combien de temps durent les coupons Size? ?
Chaque coupon a une date d'expiration indiquee dans la colonne "Expiration". Le script fetch.py renvoie uniquement les coupons actifs au moment de l'execution.

### Ou trouver les bons de reduction Size? les plus recents ?
La page [shopilo.fr/reductions/sizeofficial.fr](https://shopilo.fr/reductions/sizeofficial.fr) est mise a jour quotidiennement avec les codes promo Size?, bons de reduction Size? et coupons promotionnels Size? les plus recents.

### Le code ne fonctionne pas. Que faire ?
Verifiez la date d'expiration et les conditions (montant minimum de commande, produits eligibles). Certains codes sont valables uniquement sur l'application mobile ou pour la premiere commande.

## A propos de Size?

Size? est l'une des boutiques en ligne les plus populaires. Sur [shopilo.fr](https://shopilo.fr/reductions/sizeofficial.fr), retrouvez les meilleurs codes promo Size?, coupons Size? verifies et bons de reduction Size? actifs, mis a jour chaque jour.

## Installation npm

```bash
npm install code-promo-sizeofficial
```

```javascript
const { fetchCoupons } = require('code-promo-sizeofficial');
fetchCoupons().then(data => console.log(data));
```

## Licence

MIT, donnees extraites de [shopilo.fr](https://shopilo.fr)
