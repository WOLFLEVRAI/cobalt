<script lang="ts">
    import { t } from "$lib/i18n/translations";
    import SectionHeading from "$components/misc/SectionHeading.svelte";
</script>

<section id="general">
<SectionHeading
    title={$t("about.heading.general")}
    sectionId="general"
/>

ces termes s’appliquent uniquement lors de l’utilisation de l’instance officielle de cobalt.
dans d’autres cas, il faudra contacter l’hébergeur de l’instance pour obtenir des infos précises.
</section>

<section id="saving">
<SectionHeading
    title={$t("about.heading.saving")}
    sectionId="saving"
/>

la fonction de sauvegarde simplifie le téléchargement de contenu depuis Internet,
et nous déclinons toute responsabilité sur l’usage du contenu sauvegardé.

les serveurs de traitement fonctionnent comme des proxies avancés et n’écrivent jamais de contenu demandé sur le disque.
tout est géré en RAM et purgé définitivement dès que le tunnel est terminé.
nous n’avons aucun log de téléchargement et ne pouvons identifier personne.

tu peux en apprendre plus sur le fonctionnement des tunnels dans la [politique de confidentialité](/about/privacy).
</section>

<section id="responsibility">
<SectionHeading
    title={$t("about.heading.responsibility")}
    sectionId="responsibility"
/>

tu (utilisateur final) es responsable de l’usage de nos outils, de la manière dont tu utilises et diffuses le contenu résultant.
sois respectueux du travail des autres et crédite toujours les créateurs originaux.
assure-toi de ne pas violer de conditions ou licences.

pour un usage éducatif, cite toujours les sources et crédite les créateurs originaux.

le fair use et le crédit profitent à tout le monde.
</section>

<section id="abuse">
<SectionHeading
    title={$t("about.heading.abuse")}
    sectionId="abuse"
/>

nous n’avons aucun moyen de détecter automatiquement les abus car cobalt est totalement anonyme.
tu peux toutefois nous signaler ce type d’activité par email, et nous ferons de notre mieux pour intervenir manuellement : abuse[at]imput.net

**cet email n’est pas destiné au support utilisateur, tu n’obtiendras pas de réponse si ton problème n’est pas lié à un abus.**

si tu rencontres des problèmes, tu peux contacter le support via n’importe quelle méthode disponible sur [la page communauté](/about/community).
</section>
