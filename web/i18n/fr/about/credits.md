<script lang="ts">
    import { contacts, docs, partners } from "$lib/env";
    import { t } from "$lib/i18n/translations";

    import SectionHeading from "$components/misc/SectionHeading.svelte";
    import BetaTesters from "$components/misc/BetaTesters.svelte";
</script>

<section id="imput">
<SectionHeading
    title="imput"
    sectionId="imput"
/>

cobalt est créé avec amour et soin par [imput](https://imput.net/) ❤️

nous sommes une petite équipe de deux gars, mais on bosse dur pour créer un super logiciel qui profite à tout le monde.
si tu apprécies notre travail, pense à nous soutenir sur la [page des dons](/donate) !
</section>

<section id="testers">
<SectionHeading
    title={$t("about.heading.testers")}
    sectionId="testers"
/>

un énorme merci à nos testeurs pour avoir testé les mises à jour en avance et assuré leur stabilité.
ils nous ont aussi aidés à sortir cobalt 10 !
<BetaTesters />

tous les liens sont externes et mènent à leurs sites persos ou réseaux sociaux.
</section>

<section id="partners">
<SectionHeading
    title={$t("about.heading.partners")}
    sectionId="partners"
/>

une partie de l’infrastructure de traitement de cobalt
est fournie par notre partenaire de longue date, [royalehosting.net]({partners.royalehosting}) !
</section>

<section id="meowbalt">
<SectionHeading
    title={$t("general.meowbalt")}
    sectionId="meowbalt"
/>

meowbalt est la mascotte rapide de cobalt, un chat très expressif qui adore l’internet ultra rapide.

tout l’art incroyable de meowbalt que tu vois dans cobalt
a été créé par [GlitchyPSI](https://glitchypsi.xyz/).
il est aussi le créateur original du personnage.

imput détient les droits légaux sur le design du personnage de meowbalt,
mais pas sur les œuvres spécifiques créées par GlitchyPSI.

on aime meowbalt, donc quelques règles sont mises en place pour le protéger :
- tu ne peux pas utiliser le design de meowbalt sous une forme qui n’est pas du fan art.
- tu ne peux pas utiliser le design ou les œuvres de meowbalt à des fins commerciales.
- tu ne peux pas utiliser le design ou les œuvres de meowbalt dans tes propres projets.
- tu ne peux pas utiliser ou modifier les œuvres de GlitchyPSI de meowbalt sous quelque forme que ce soit.

si tu crées du fan art de meowbalt, partage-le dans
[notre serveur Discord](/about/community), on adorerait le voir !
</section>

<section id="licenses">
<SectionHeading
    title={$t("about.heading.licenses")}
    sectionId="licenses"
/>

le code de l’API cobalt (serveur de traitement) est open source et sous licence [AGPL-3.0]({docs.apiLicense}).

le code frontend de cobalt est [source first](https://sourcefirst.com/) et sous licence [CC-BY-NC-SA 4.0]({docs.webLicense}).

on a dû faire le frontend en source first pour empêcher les profiteurs de tirer avantage de notre travail
et de créer des clones malveillants qui trompent les gens et nuisent à notre identité publique.
à part l’usage commercial, ça suit les mêmes principes que beaucoup de licences open source.

on utilise beaucoup de bibliothèques open source, mais on crée aussi les nôtres.
tu peux voir la liste complète des dépendances sur [GitHub]({contacts.github}) !
</section>
