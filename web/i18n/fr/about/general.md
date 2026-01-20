<script lang="ts">
    import { t } from "$lib/i18n/translations";
    import { contacts, docs } from "$lib/env";

    import SectionHeading from "$components/misc/SectionHeading.svelte";
</script>

<section id="summary">
<SectionHeading
    title={$t("about.heading.summary")}
    sectionId="summary"
/>

cobalt t’aide à sauvegarder n’importe quoi depuis tes sites préférés : vidéos, audios, photos ou GIFs. il suffit de coller le lien et c’est parti !

pas de pubs, pas de trackers, pas de paywalls, ni d’autres trucs relous. juste une web app pratique qui fonctionne partout, à tout moment.
</section>

<section id="motivation">
<SectionHeading
    title={$t("about.heading.motivation")}
    sectionId="motivation"
/>

cobalt a été créé pour le bien public, pour protéger les gens des pubs et malwares poussés par d’autres téléchargeurs.
nous croyons que le meilleur logiciel est sûr, open et accessible. tous les projets imput suivent ces principes de base.
</section>

<section id="privacy-efficiency">
<SectionHeading
    title={$t("about.heading.privacy_efficiency")}
    sectionId="privacy-efficiency"
/>

toutes les requêtes vers le backend sont anonymes et toutes les infos sur les éventuels tunnels de fichiers sont chiffrées.
nous appliquons une politique stricte de zéro logs et ne stockons ni ne suivons *rien* sur les personnes.

si une requête nécessite un traitement supplémentaire, comme le remux ou le transcodage, cobalt traite les médias
directement sur ton appareil. cela garantit la meilleure efficacité et confidentialité.

si ton appareil ne supporte pas le traitement local, un traitement live côté serveur est utilisé à la place.
dans ce cas, les médias traités sont streamés directement vers le client, sans jamais être stockés sur le disque du serveur.

tu peux [activer le tunneling forcé](/settings/privacy#tunnel) pour booster encore plus la confidentialité.
une fois activé, cobalt tunnelera tous les fichiers téléchargés, pas seulement ceux qui en ont besoin.
personne ne saura d’où tu télécharges quelque chose, même pas ton fournisseur d’accès.
tout ce qu’ils verront, c’est que tu utilises une instance cobalt.
</section>

<section id="community">
<SectionHeading
    title={$t("about.heading.community")}
    sectionId="community"
/>

cobalt est utilisé par d’innombrables artistes, enseignants et créateurs de contenu pour faire ce qu’ils aiment.
nous restons toujours en contact avec notre communauté et travaillons ensemble pour rendre cobalt encore plus utile.
n’hésite pas à [rejoindre la conversation](/about/community) !

nous croyons que l’avenir d’internet est ouvert, c’est pourquoi cobalt est
[source first](https://sourcefirst.com/) et [facilement auto-hébergeable]({docs.instanceHosting}).

si ton pote héberge une instance de traitement, demande-lui simplement le domaine et [ajoute-le dans les paramètres d’instance](/settings/instances#community).

tu peux consulter le code source et contribuer [sur GitHub]({contacts.github}) à tout moment.
toutes les contributions et suggestions sont les bienvenues !
</section>
