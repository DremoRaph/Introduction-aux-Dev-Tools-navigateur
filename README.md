# Introduction aux Dev Tools navigateur


Ce guide est une introduction à l'usage **basique** des outils pour développeurs des navigateurs, communément appelés *Dev tools*, pour faciliter le **développement** et la **résolution de problèmes** en développement web. Le guide présente d'abord l'utilisation des outils et ensuite partage des cas d'utilisations/erreurs communs où l'application des *dev tools* devraient être un reflex. Sachez que ce guide, bien qu'il soit en français, montrera des exemples avec un paramétrage **en anglais**. La raison est que la plupart des références, guides et documentations sont plus nombreuses ou même précises en anglais, donc se familiariser avec l'interface et les termes en anglais est souvent plus concret.

## 1. Qu'est-ce que les *dev tools*?

Les *dev tools* sont des regroupements d'outils mis à disposition aux développeurs à même les navigateurs web pour **faciliter certaines tâches**, dont primairement la **collecte d'information** sur ce qui se passe dans votre navigateur. Puisque les outils sont implémantés au sein même du navigateur, ils **peuvent différer entre chacuns**. Le "modèle" le plus répandu est celui des *dev tools* de [Google Chrome](https://developer.chrome.com/docs/devtools/). Puisqu'ils sont basés sur **Chromium**, le moteur derière Chrome, les mêmes outils sont retrouvés dans les autres navigateurs l'utilisant, soit [Opera](https://www.opera.com/)/[Opera GX](https://www.opera.com/gx), [Microsoft Edge](https://www.microsoft.com/en-us/edge) et une multitude d'autres, incluant même des modules n'étant pas des navigateurs comme [Electron Js](https://www.electronjs.org/). 

![Exemple Chromium](./src/ExempleChromium.png)

L'autre version la plus répandue sont les *dev tools* du navigateur [Firefox](https://developer.mozilla.org/en-US/docs/Tools). Les deux sont semblables, les différences les plus notoires étant que les fonctionalités, même si elles sont presque identiques, sont séparées dans des sous-menus différents.

![Exemple FireFox](./src/ExempleFireFox.png)

Puisque les navigateurs sur Chromium sont plus populaires, **la suite de ce guide se suivra sur sa version des devtools**. Sachez que si vous utilisez Firefox, vous avez quand même accès à la plupart ou même la totalité des fonctionalités, donc ce n'est pas très grave!

