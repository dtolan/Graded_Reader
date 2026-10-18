# Review: Le chariot qui grince

Genre: everyday · text checked: C1 · checker: claude-sonnet-5-5 · 2026-10-18

This is a model's second opinion to speed up a human review. Check every flagged item, and the `uncertain` ones, against a reliable source, then run `review_book.py approve`.

## Chapter 1: Vingt minutes, pas une de plus
Verdict: **ok**

| Key fact | In text | Accuracy | Note |
|---|---|---|---|
| Trolleys are unlocked with a one-euro coin or token that you get back when you return the trolley. | yes | confident |  |
| ⚠ Large supermarkets are on the outskirts of towns, with a big car park and separate entrance and exit. | partly | confident | The chapter mentions the edge-of-town location and the car park but not the separate entrance and exit. |
| Single-use plastic checkout bags have been banned in France since 2016, so people bring reusable bags. | yes | confident |  |
| Supermarkets are often closed on Sunday afternoon or all day Sunday, so Saturday morning is busy. | yes | confident |  |
| Many supermarkets offer a drive (click-and-collect) where you order online and collect from your car. | yes | confident |  |

## Chapter 2: Le rayon des tentations
Verdict: **minor_issues**

| Key fact | In text | Accuracy | Note |
|---|---|---|---|
| Loose fruit and vegetables are weighed by the customer on a self-service scale that prints a price label with a barcode. | yes | confident |  |
| Shelf labels must show the price per kilo or litre, allowing comparison. | yes | confident |  |
| Own-brand products (marques de distributeur) are usually cheaper than national brands. | yes | confident | The text does not name Marque Repère or Carrefour, but the fact itself is covered. |
| Supermarkets place special offers and loss leaders on têtes de gondole to encourage impulse buying. | yes | confident |  |
| Loyalty cards give points, discount vouchers or personalised offers. | yes | confident | The text mentions the card and vouchers, not points. |
| ⚠ Frozen section is les surgelés; products carry a DLC for fresh food or a DDM for dry goods. | partly | confident | The chapter mentions the surgelés and the DDM on biscuits, but not the DLC. |

Issues in the text:
- **medium** “Un kilo deux cents, trois euros quarante. » Madame Roux lit par-dessus son épaule. « Trois euros quarante le kilo.” — 3.40 € is first given as the total price for 1.2 kg, then as the price per kilo. The two are inconsistent.
- **low** “des soldes de saison sur des plats à gratin” — In France, 'soldes' is a legally regulated term limited to set periods. A supermarket promotion would not be called that.

## Chapter 3: Boucherie, boulangerie et compagnie
Verdict: **minor_issues**

| Key fact | In text | Accuracy | Note |
|---|---|---|---|
| Supermarkets have staffed butcher's, bakery and deli counters where you take a ticket and wait your turn. | yes | confident |  |
| A baguette de tradition costs about one euro and by law has no additives. | yes | confident | 1.10 euros is consistent; the additive-free claim is correct under the 1993 decree. |
| ⚠ A dozen eggs is une douzaine d'œufs; eggs are sold unrefrigerated with a number code. | no | confident | Eggs are only mentioned in the last line; the dozen, shelf storage and code are not covered. |
| ⚠ Packaged food shows a DLC or a DDM. | partly | confident | The chapter only says 'date de péremption'; DLC and DDM are not named. |
| ⚠ Typical staples include bread, butter, cheese, yoghurt, ham, pasta, rice, flour, sugar, biscuits and wine. | partly | confident | Most items appear (bread, ham, pasta, cheese, biscuits, butter, wine); rice, flour, sugar and yoghurt do not. |
| Juice, wine and water are often sold in multipacks, e.g. six bottles of water. | yes | confident | Water in packs of six is mentioned. |

Issues in the text:
- **low** “Date de péremption : demain.” — The official labels are DLC ('à consommer jusqu'au') or DDM. 'Date de péremption' is a colloquial term, and this is a missed chance to teach the right term.

## Chapter 4: La queue interminable
Verdict: **minor_issues**

| Key fact | In text | Accuracy | Note |
|---|---|---|---|
| French supermarkets have staffed checkouts, self-checkouts and often a priority checkout for pregnant women, disabled and elderly people. | yes | confident |  |
| On conveyor belts, customers use a small plastic divider bar to separate their shopping from the next person's. | yes | confident |  |
| Self-checkouts say 'Veuillez patienter, un instant' and 'Il y a une anomalie dans le sac' when the bag weight differs from expected. | yes | confident |  |
| ⚠ Cashiers say 'Bonjour' to every customer and 'Merci, bonne journée' at the end, and customers greet back. | partly | confident | Bonjour is shown and returned, but 'Merci, bonne journée' is said to Madame Roux at the start, not at the end of a transaction. |
| ⚠ Security guards may be posted near the exit of large supermarkets and can ask to see receipts or bags. | no | confident | No security guard appears in this chapter; the fact is not used. |

Issues in the text:
- **medium** “Josiane la salue d'un signe de tête : « Merci, bonne journée ! »” — 'Merci, bonne journée' is a closing formula said at the end of a purchase; used as a greeting to Madame Roux, who is not leaving, it misrepresents the custom.
- **low** “« Il manque un article. »” — Self-checkouts typically say 'article inattendu' or ask to place the item in the bagging area; 'Il manque un article' is not a typical message, though plausible.

## Chapter 5: Le coup de bambou
Verdict: **minor_issues**

| Key fact | In text | Accuracy | Note |
|---|---|---|---|
| Contactless card payments in France are limited to a single transaction of 50 euros, above which you must enter the PIN. | yes | confident |  |
| ⚠ French bank cards use a four-digit PIN and many terminals ask for it after several contactless payments in a row. | partly | confident | Four-digit PIN is shown; the repeated-contactless prompt is not mentioned. |
| ⚠ Tipping is not expected at French supermarkets; service is included in cafés and restaurants. | no | confident | Not addressed in the chapter. |
| ⚠ Shoppers keep their receipt as proof of purchase for refunds or exchanges. | partly | confident | Receipt appears only at the end, with no mention of refunds or exchanges. |
| Cash is still accepted at French supermarket checkouts, though cashiers may ask for the exact change (l'appoint). | yes | confident |  |
| ⚠ The euro is divided into 100 cents, and banknotes come in 5, 10, 20, 50, 100, 200 and 500 euros. | no | confident | Denominations are not listed; only 20 and 10 euro notes and a 2-euro coin appear. The 500 note is no longer issued, though still legal tender. |

Issues in the text:
- **low** “L'addition est exactement trois fois trop élevée.” — 178.40 euros against a 60 euro budget is just under three times, not exactly three times (and 'three times too high' is loose).

## Chapter 6: Le dîner de la dernière chance
Verdict: **ok**

| Key fact | In text | Accuracy | Note |
|---|---|---|---|
| French dinners traditionally include several courses: an entrée, a plat, cheese, and a dessert. | yes | confident |  |
| In France, the cheese course comes before dessert and is often served with bread rather than with crackers. | yes | confident |  |
| ⚠ Typical French supermarkets sell fresh produce, packaged food, drinks, household items and often have in-store loyalty programmes. | partly | confident | The chapter shows food, wine and a discount voucher; no loyalty programme or household items. |
| The French often say 'bon appétit' before eating and 'à votre santé' or 'santé !' when raising a glass. | yes | confident |  |
| Since 2016 French law forbids large supermarkets from destroying unsold edible food, and they must donate it to charities. | yes | confident | The text mentions the law and donation to associations without giving the year. |
