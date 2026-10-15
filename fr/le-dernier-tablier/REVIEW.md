# Review: Le dernier tablier

Genre: fiction · text checked: B1 · checker: claude-sonnet-5-5 · 2026-10-15

This is a model's second opinion to speed up a human review. Check every flagged item, and the `uncertain` ones, against a reliable source, then run `review_book.py approve`.

## Chapter 1: Le train de Paris
Verdict: **ok**

| Key fact | In text | Accuracy | Note |
|---|---|---|---|
| Lyon has two main train stations: Part-Dieu and Perrache; Paris–Lyon is about two hours by TGV from Gare de Lyon. | yes | confident |  |
| The Croix-Rousse is a hill north of the Presqu'île, historically known as 'la colline qui travaille' because of the silk workers (canuts). | yes | confident |  |
| A bouchon is a traditional Lyon restaurant serving local cuisine in a convivial setting, often with checked tablecloths and a short menu. | yes | confident | Checked tablecloths and the convivial setting are shown; the short menu is not mentioned. |
| ⚠ Lyon is often called the gastronomic capital of France; Paul Bocuse and the 'mères lyonnaises' helped build this reputation. | no | confident | Not mentioned in this chapter; the claim itself is accurate. |
| The Croix-Rousse is reached from the centre by metro line C, a rack-railway line unusual for its cog system. | yes | confident |  |

## Chapter 2: Les mères lyonnaises
Verdict: **ok**

| Key fact | In text | Accuracy | Note |
|---|---|---|---|
| The 'mères lyonnaises' were women cooks, such as Eugénie Brazier, who turned family cooking into restaurant fame in the early 20th century. | yes | confident |  |
| Eugénie Brazier was the first chef to obtain three Michelin stars twice, in 1933, for two restaurants. | yes | confident | Chapter says 1933, three stars for two restaurants at once; accurate. |
| Typical bouchon dishes include quenelles de brochet, tablier de sapeur, andouillette, salade lyonnaise, cervelle de canut and saucisson brioché. | yes | confident |  |
| The 'Bouchon Lyonnais' label is a quality label created to protect authentic bouchons from imitations. | yes | confident |  |
| 'Tablier de sapeur' is breaded and fried tripe, traditionally served with sauce gribiche. | yes | confident |  |
| Cervelle de canut is a fresh cheese spread with herbs, shallots, garlic, oil and vinegar, not actual brains. | yes | confident |  |

## Chapter 3: Le marché du boulevard
Verdict: **minor_issues**

| Key fact | In text | Accuracy | Note |
|---|---|---|---|
| The Croix-Rousse market takes place along the Boulevard de la Croix-Rousse and is open every morning except Monday. | yes | confident |  |
| The market is known as one of Lyon's most popular open-air food markets, with producers selling vegetables, cheeses, charcuterie and flowers. | yes | confident |  |
| Saint-Marcellin and Saint-Félicien are cheeses from the Rhône-Alpes region often found at Lyon markets. | yes | confident |  |
| ⚠ Lyon sits between the Rhône and Saône rivers, near the Monts du Lyonnais, a rural area supplying produce. | partly | confident | The chapter mentions the Monts du Lyonnais as a supplying region but not the two rivers. |
| Cardon gratiné, a thistle-like vegetable dish, is a traditional Lyon winter specialty. | yes | confident |  |
| ⚠ Lyon's famous Halles Paul Bocuse market is in the Part-Dieu district, a different place from the Croix-Rousse market. | no | confident | The chapter never mentions the Halles Paul Bocuse or Part-Dieu. |

Issues in the text:
- **medium** “Nadia Benali avait trente-quatre ans, cinq de plus que Camille l'avait connue enfant dans la cour de l'école” — The sentence is garbled. It implies an age gap of five years, which contradicts the two women being school friends who have known each other since age six.

## Chapter 4: Quenelle ou pas quenelle
Verdict: **ok**

| Key fact | In text | Accuracy | Note |
|---|---|---|---|
| Quenelles de brochet are light dumplings made from pike, flour, butter and eggs, usually served in a sauce Nantua made with crayfish. | yes | confident |  |
| The quenelle is a Lyon speciality, poached rather than fried, and baked in sauce until puffed. | yes | confident |  |
| Sauce Nantua is named after the town of Nantua in the Ain department, known for its crayfish. | yes | confident |  |
| Praline tarts, tarte aux pralines roses, are a classic Lyon dessert made with pink sugar-coated almonds. | yes | confident |  |
| Traditional Lyon cooking relies heavily on butter, cream, pork and offal, reflecting the city's working-class history. | yes | confident |  |

## Chapter 5: Les traboules
Verdict: **minor_issues**

| Key fact | In text | Accuracy | Note |
|---|---|---|---|
| Traboules are covered passages through buildings that let people cross between streets; Lyon has hundreds, in Vieux Lyon and the Croix-Rousse. | yes | confident |  |
| The canuts were silk workers; the Croix-Rousse buildings have very high ceilings to fit the Jacquard looms. | yes | confident |  |
| The Jacquard loom was invented by Joseph Marie Jacquard, born in Lyon in 1752. | yes | confident |  |
| Traboules were used by members of the Resistance during the Second World War to avoid German patrols. | yes | confident |  |
| Vieux Lyon is a UNESCO World Heritage site, inscribed in 1998 for the historic site of Lyon. | yes | confident |  |
| ⚠ The Révolte des canuts took place in 1831 and 1834 over working conditions and pay. | no | confident | The claim is accurate, but the chapter never mentions the revolts. |

Issues in the text:
- **medium** “Elles ont pris le funiculaire, puis elles ont descendu la colline vers la Saône.” — The Croix-Rousse funicular (la ficelle) was closed in 1967; the Vieux Lyon funiculars go to Fourvière and do not link the Croix-Rousse to the Saône. The route described is doubtful.
- **low** “Cette traboule-là, je la connais depuis soixante-quinze ans. Pendant la guerre, des résistants s'en servaient” — Odette is 82; knowing the traboule for 75 years while carrying messages as a small child during the war is hard to reconcile (she would have been a toddler or an infant in 1940-44).

## Chapter 6: Ce que dit le critique
Verdict: **ok**

| Key fact | In text | Accuracy | Note |
|---|---|---|---|
| Salade lyonnaise traditionally combines frisée lettuce, lardons, croutons and a poached egg with a vinaigrette. | yes | confident |  |
| The Beaujolais region supplies the light red wines traditionally served in bouchons, often in a 46 cl 'pot'. | yes | confident |  |
| Lyon's pot lyonnais is a thick-bottomed 46 cl bottle used for serving wine. | yes | confident |  |
| The Beaujolais Nouveau is released on the third Thursday of November. | yes | confident |  |
| Rosette de Lyon is a dry-cured pork sausage, a classic starter in bouchons. | yes | confident | The text presents it as the start of the meal in a bouchon, consistent with the fact. |
| Gratin dauphinois is not Lyonnais but from the Dauphiné; Lyon bouchons more typically serve potatoes sautéed or with cervelas. | yes | confident |  |

## Chapter 7: Un pot de Beaujolais
Verdict: **ok**

| Key fact | In text | Accuracy | Note |
|---|---|---|---|
| Beaujolais Nouveau is released at midnight on the third Thursday of November, with the slogan 'Le Beaujolais nouveau est arrivé !'. | yes | confident |  |
| Beaujolais wines are made from the Gamay grape. | yes | confident | Red Beaujolais is Gamay; white Beaujolais exists but the character's simplification is fine. |
| The Fête des Lumières takes place around 8 December in Lyon and lasts about four days. | yes | confident |  |
| The Fête des Lumières originates from 1643, when Lyon's inhabitants promised to honour the Virgin Mary if the city was spared the plague. | yes | confident |  |
| In 1852 the inauguration of a statue of the Virgin Mary on Fourvière hill was delayed by bad weather, and residents placed candles in their windows. | yes | confident | Tradition usually cites a Saône flood or bad weather. |
| The Basilique Notre-Dame de Fourvière overlooks the city and is a symbol of Lyon. | yes | confident |  |

## Chapter 8: Les lumignons
Verdict: **ok**

| Key fact | In text | Accuracy | Note |
|---|---|---|---|
| Lumignons on window sills on the evening of 8 December | yes | confident |  |
| Place des Terreaux light projections on the Hôtel de Ville facade | yes | confident |  |
| Millions of visitors, artists create installations across the city | yes | confident |  |
| Pogne de Romans is a brioche-like specialty from the Drôme, found in Lyon bakeries | yes | confident |  |
| Lyon bugnes are fried dough fritters eaten around Mardi Gras | yes | confident | Text says 'au carnaval', which is equivalent. |
| Praline Rose appears in the brioche aux pralines, sold in many boulangeries | yes | confident |  |

## Chapter 9: Soir de fête
Verdict: **ok**

| Key fact | In text | Accuracy | Note |
|---|---|---|---|
| On 8 December, tens of thousands of candles are lit in windows across Lyon, and the streets are crowded with pedestrians. | yes | confident |  |
| The city's traffic is heavily restricted during the Fête des Lumières and visitors move on foot or by metro. | yes | confident |  |
| ⚠ Lyon's Saint-Jean cathedral lies in Vieux Lyon, while Fourvière looks over the city from the west bank of the Saône. | partly | confident | Chapter mentions Fourvière on its hill but never mentions Saint-Jean cathedral. |
| Many Lyon restaurants offer a 'menu' with a starter, a main course and a cheese or dessert. | yes | confident |  |
| The cheese course in Lyon often features fresh cervelle de canut or Saint-Marcellin. | yes | confident |  |

## Chapter 10: Le tablier se transmet
Verdict: **ok**

| Key fact | In text | Accuracy | Note |
|---|---|---|---|
| A bouchon often passes from generation to generation in the same family, with recipes kept in handwritten notebooks. | yes | confident |  |
| The Croix-Rousse market is a weekly ritual where chefs and residents shop for seasonal produce. | yes | confident |  |
| In Lyon, winter produce includes cardons, chestnuts, leeks, celeriac and Jerusalem artichokes. | yes | confident |  |
| The tarte à la praline is often served at the end of a meal in Lyon, with its pink colour recognisable at pâtisseries. | yes | confident | Text mentions it served pink at the end of the meal; pâtisserie recognition not mentioned, which is fine. |
| ⚠ The apron, 'le tablier', is a symbol of cooking trades in France, and the name 'tablier de sapeur' plays on it. | partly | confident | The apron as sign of the trade is stated; the tablier de sapeur wordplay is only alluded to, not explained. |
