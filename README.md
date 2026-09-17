# hb-aide<!-- Systeme.io : colle tout ce bloc dans un élément "HTML" / "Code personnalisé" -->
<div id="hb-page">

<div class="grain"></div>

<div class="wrap">
  <header class="site" id="site-header">
    <div class="brand">
      <span class="brand-mark"><span class="brand-dot"></span></span>
      <span>Hello bank! — Parrainage</span>
    </div>
    <nav class="site">
      <a href="#comment-ca-marche">Comment ça marche</a>
      <a href="#prime">Les primes</a>
      <a href="#faq">Questions</a>
      <!-- Remplacez ce lien par l'URL de votre page "Guide complet" une fois publiée sur systeme.io -->
      <a href="#guide-complet-a-remplacer">Guide complet</a>
      <a href="#form" class="btn-nav">Je me lance</a>
    </nav>
  </header>
</div>

<div class="wrap">
  <section class="hero">
    <div class="hero-grid">
      <div class="hero-copy">
        <p class="kicker">Un client Hello bank! vous invite</p>
        <h1>Ouvrez un compte Hello bank!, et on touche une prime chacun.</h1>
        <p class="lede">Je suis déjà client Hello bank! et je peux vous parrainer. Vous ouvrez votre compte en ligne en quelques minutes, vous touchez votre prime de bienvenue, et je touche la mienne en tant que parrain. Laissez-moi vos coordonnées, je vous envoie l'invitation officielle directement depuis mon espace client.</p>
        <div class="hero-ctas">
          <a href="#form" class="btn btn-primary">Je veux être parrainé(e)</a>
          <a href="#prime" class="btn btn-ghost">Voir le détail des primes</a>
        </div>
      </div>

      <div class="hero-orbit">
        <div class="orbit-ring ring-a"></div>
        <div class="orbit-ring ring-b"></div>
        <div class="orbit-dot"></div>

        <div class="node-card node-you">
          <div class="node-label">Filleul(e) — vous</div>
          <div class="node-amount">jusqu'à <span class="num">280 €</span><sup>*</sup></div>
        </div>

        <div class="node-card node-friend">
          <div class="node-label">Parrain — moi</div>
          <div class="node-amount">jusqu'à <span class="num">140 €</span></div>
        </div>
      </div>
    </div>
  </section>
</div>

<div class="wrap">
  <section id="comment-ca-marche" class="eyebrow-free">

    <div class="section-head">
      <h2>Comment se passe l'ouverture du compte</h2>
      <p>Tout se fait en ligne, sans agence, en général en moins de 10 minutes de votre côté.</p>
    </div>

    <div class="steps">

      <div class="step">
        <div class="step-num">1</div>
        <div>
          <h3>Vous me laissez vos coordonnées</h3>
          <p>Prénom, nom et email dans le formulaire un peu plus bas. Ça ne prend pas plus de 30 secondes et ça ne vous engage à rien tant que vous n'avez pas ouvert de compte.</p>
        </div>
      </div>

      <div class="step">
        <div class="step-num">2</div>
        <div>
          <h3>Je vous envoie une invitation officielle</h3>
          <p>Depuis mon espace client Hello bank! (bouton « Je parraine »), je vous envoie une invitation par email ou SMS. C'est ce lien-là, et uniquement celui-ci, qui déclenche le parrainage — c'est important pour que vous receviez bien votre prime.</p>
        </div>
      </div>

      <div class="step">
        <div class="step-num">3</div>
        <div>
          <h3>Vous remplissez le formulaire en ligne</h3>
          <p>Identité, adresse, situation. Une pièce d'identité et un selfie ou une signature électronique suffisent généralement pour vérifier votre identité — aucun premier versement n'est nécessaire pour ouvrir le compte.</p>
        </div>
      </div>

      <div class="step">
        <div class="step-num">4</div>
        <div>
          <h3>La banque valide et active votre compte</h3>
          <p>Hello bank! vérifie le dossier et active le compte. C'est cette activation, confirmée par la banque, qui déclenche officiellement le parrainage — pas la simple inscription.</p>
        </div>
      </div>

      <div class="step">
        <div class="step-num">5</div>
        <div>
          <h3>Les primes sont versées</h3>
          <p>Ma prime de parrain est en général créditée dans les 20 jours suivant l'activation de votre compte. Votre prime de bienvenue suit ses propres conditions (paiements/retraits selon la formule choisie), détaillées plus bas.</p>
        </div>
      </div>

    </div>

    <div class="steps-cta">
      <!-- Remplacez ce lien par l'URL de votre page "Guide complet" une fois publiée sur systeme.io -->
      <a href="#guide-complet-a-remplacer" class="link-arrow">Voir le guide détaillé, pièce par pièce, étape par étape</a>
    </div>

  </section>
</div>

<div class="wrap">
  <section id="form" class="eyebrow-free">

    <div class="section-head">
      <h2>On se lance ?</h2>
      <p>Laissez-moi vos coordonnées ci-dessous. Elles me sont transmises directement et en toute sécurité — vous n'avez rien d'autre à faire. Je reviens vers vous avec l'invitation officielle, généralement sous 24 à 48h.</p>
    </div>

    <div class="form-panel">

      <form id="lead-form" novalidate>

        <div class="field-row">
          <div class="field">
            <label for="prenom">Prénom</label>
            <input type="text" id="prenom" name="prenom" required autocomplete="given-name">
          </div>
          <div class="field">
            <label for="nom">Nom</label>
            <input type="text" id="nom" name="nom" required autocomplete="family-name">
          </div>
        </div>

        <div class="field-row">
          <div class="field">
            <label for="email">Email</label>
            <input type="email" id="email" name="email" required autocomplete="email">
          </div>
          <div class="field">
            <label for="telephone">Téléphone <span class="optional">(optionnel)</span></label>
            <input type="tel" id="telephone" name="telephone" autocomplete="tel" placeholder="Pour l'invitation par SMS">
          </div>
        </div>

        <button type="submit" class="btn btn-primary btn-block" id="submit-btn">
          <span class="btn-label">Recevoir mon invitation</span>
        </button>

        <p class="form-note">
          Vos coordonnées servent uniquement à vous envoyer l'invitation de parrainage. Une question avant de vous lancer ? Voir plus bas comment me la poser directement.
        </p>

        <div id="confirm-msg" role="status"></div>

      </form>

    </div>

  </section>
</div>

<div class="wrap">
  <section id="prime" class="eyebrow-free">

    <div class="section-head">
      <h2>Ce que rapporte réellement le parrainage</h2>
      <p>Les montants dépendent de l'offre choisie (Hello One, gratuite, ou Hello Prime) et des promotions en cours. Voici ce qui est annoncé par Hello bank! au moment de la rédaction de cette page — vérifiez toujours les conditions exactes en vigueur avant de vous engager.</p>
    </div>

    <div class="prime-grid">

      <div class="prime-card">
        <div class="who">Vous, en tant que filleul(e)</div>
        <div class="amount">jusqu'à <span class="num">280 €</span></div>
        <ul>
          <li><strong>80 €</strong> de prime de bienvenue, versée que vous choisissiez Hello One ou Hello Prime, sous réserve d'au moins 5 paiements ou retraits par carte par mois pendant les 3 premiers mois entiers de détention de l'offre.</li>
          <li>Jusqu'à <strong>200 €</strong> de bon d'achat supplémentaire si vous transférez votre ancienne banque vers Hello bank! via le service de mobilité bancaire Hello Start+ — cette partie n'est pas automatique, elle dépend de votre situation.</li>
          <li><strong>Hello One</strong> : carte gratuite dès le départ, tant que vous faites au moins un paiement ou un retrait par mois (sinon 6 €/mois).</li>
          <li><strong>Hello Prime</strong> : carte offerte pendant les 6 premiers mois, puis gratuite au-delà si vous versez au moins 1 500 €/mois sur le compte (sinon 6 €/mois, 9 €/mois pour Hello Prime Duo).</li>
        </ul>
      </div>

      <div class="prime-card prime-card-featured">
        <div class="who">Moi, en tant que parrain</div>
        <div class="amount">jusqu'à <span class="num">140 €</span></div>
        <ul>
          <li>Versée dès que votre compte est validé et activé par la banque, en général dans les 20 jours suivants.</li>
          <li>Le montant exact (120 € ou 140 €) dépend des conditions en vigueur au moment de l'opération.</li>
          <li>Limitée à 10 parrainages réussis par année civile.</li>
          <li>Non versée si vous étiez déjà client Hello bank! ou déjà parrainé(e) par quelqu'un d'autre.</li>
        </ul>
      </div>

    </div>

  </section>
</div>

<div class="wrap">
  <section class="eyebrow-free">

    <div class="total-block">
      <div>
        <h3>Le plafond légal du parrainage Hello bank!</h3>
        <p>Chaque client peut parrainer jusqu'à 10 personnes par année civile. Avec une prime de 120 à 140 € par filleul validé, voici le maximum qu'un parrain peut toucher sur douze mois — à condition, bien sûr, de trouver 10 personnes intéressées et que chacune ouvre et garde son compte au moins un an.</p>
      </div>
      <div class="num-wrap">
        <div class="num-big">1 200–1 400 €</div>
        <div class="num-cap">par an, pour 10 filleuls</div>
      </div>
    </div>

  </section>
</div>

<div class="wrap">
  <section class="eyebrow-free">

    <div class="section-head">
      <h2>Et si vous aussi, vous vouliez parrainer ?</h2>
      <p>Une fois votre compte ouvert via mon invitation, vous pouvez, vous aussi, parrainer vos propres proches et toucher les mêmes primes que moi. Si vous voulez de l'aide pour trouver vos premiers filleuls ou pour bien lancer vos parrainages, je peux vous accompagner.</p>
    </div>

    <div class="helper-box">
      <div class="helper-icon">🧭</div>
      <div class="helper-copy">
        <h3>Je peux vous aider à trouver vos filleuls</h3>
        <p>C'est un service que je propose en plus, en dehors du programme officiel de Hello bank! : une fois que vous avez ouvert votre compte avec moi, écrivez-moi à l'adresse ci-dessous si vous voulez que je vous aide à identifier des filleuls potentiels et/ou à vous inscrire correctement en tant que parrain, contre une commission à convenir ensemble.</p>
        <a href="mailto:parrainnageaide@gmail.com?subject=Je%20veux%20parrainer%20%C3%A0%20mon%20tour" class="btn btn-ghost">parrainnageaide@gmail.com</a>
      </div>
    </div>

  </section>
</div>

<div class="wrap">
  <section class="eyebrow-free">

    <div class="contact-box">
      <div class="contact-icon">✉️</div>
      <div>
        <h3>Une question avant de vous lancer ?</h3>
        <p>Pas besoin de formulaire compliqué : écrivez-moi directement, je réponds personnellement à chaque message, généralement sous 24 à 48h.</p>
      </div>
      <a href="mailto:parrainnageaide@gmail.com?subject=Question%20parrainage%20Hello%20bank%21" class="btn btn-primary">
        parrainnageaide@gmail.com
      </a>
    </div>

  </section>
</div>

<div class="wrap">
  <section id="faq" class="eyebrow-free">

    <div class="section-head">
      <h2>Questions fréquentes</h2>
      <p>Les réponses les plus utiles avant de se lancer. Une autre question ? Le contact est juste au-dessus.</p>
    </div>

    <details class="faq-item">
      <summary class="faq-q">Est-ce que c'est vraiment gratuit d'ouvrir un compte ?<span class="plus"></span></summary>
      <div class="faq-a">Aucun frais d'ouverture ni de fermeture, quelle que soit la formule, et aucun premier versement n'est exigé pour ouvrir le compte. Ensuite, ça dépend de la carte choisie : <strong>Hello One</strong> reste à 0 €/mois tant que vous faites au moins un paiement ou un retrait dans le mois (sinon 6 €/mois) — c'est une condition permanente, pas une promotion temporaire. <strong>Hello Prime</strong> est offerte pendant les 6 premiers mois (au lieu de 5 €/mois, ou 8 €/mois pour Hello Prime Duo), puis passe à 0 €/mois si vous versez au moins 1 500 €/mois sur le compte (sinon 6 €/mois, 9 €/mois pour Hello Prime Duo).</div>
    </details>

    <details class="faq-item">
      <summary class="faq-q">Puis-je bénéficier du parrainage si j'ai déjà eu un compte Hello bank! ?<span class="plus"></span></summary>
      <div class="faq-a">Non. L'offre est réservée aux personnes qui n'ont jamais eu de compte (y compris un compte joint) chez Hello bank!. Si c'est votre cas, l'ouverture ne déclenchera pas de prime, ni pour vous ni pour moi.</div>
    </details>

    <details class="faq-item">
      <summary class="faq-q">Que se passe-t-il si je ferme mon compte rapidement ?<span class="plus"></span></summary>
      <div class="faq-a">Le compte et la carte doivent être conservés au moins un an. En cas de clôture anticipée, Hello bank! se réserve le droit de reprendre le montant des primes déjà versées, à vous comme à moi.</div>
    </details>

    <details class="faq-item">
      <summary class="faq-q">Dois-je passer par votre lien pour que le parrainage compte ?<span class="plus"></span></summary>
      <div class="faq-a">Oui, c'est indispensable. L'invitation doit être envoyée par moi, depuis mon espace client ou l'application Hello bank!, avant que vous ne commenciez votre inscription. Si vous démarrez une demande de compte sans passer par cette invitation, le parrainage ne peut plus être appliqué a posteriori — d'où l'intérêt de me laisser vos coordonnées d'abord.</div>
    </details>

    <details class="faq-item">
      <summary class="faq-q">Quels documents dois-je préparer ?<span class="plus"></span></summary>
      <div class="faq-a">Une pièce d'identité valide et un justificatif de domicile suffisent dans la plupart des cas. Un RIB à votre nom n'est demandé que si vous choisissez le versement initial comme méthode de vérification d'identité. Pour Hello Prime, un justificatif de revenus est aussi demandé. Le détail complet, avec les cas particuliers, est dans mon guide complet.</div>
    </details>

    <details class="faq-item">
      <summary class="faq-q">Combien de temps pour recevoir la prime ?<span class="plus"></span></summary>
      <div class="faq-a">Ma prime de parrain est en général versée dans les 20 jours suivant l'activation définitive de votre compte. Votre prime de bienvenue à vous suit ses propres conditions d'usage (nombre de paiements/retraits selon l'offre), en général sous quelques mois.</div>
    </details>

    <details class="faq-item">
      <summary class="faq-q">Puis-je moi aussi devenir parrain après mon inscription ?<span class="plus"></span></summary>
      <div class="faq-a">Oui, tout client Hello bank! peut parrainer. Une fois votre compte ouvert via mon invitation, vous pouvez parrainer vos propres proches depuis votre espace client. Si vous voulez un coup de main pour trouver vos premiers filleuls, je propose de vous accompagner contre une commission — voir la section juste au-dessus des questions fréquentes.</div>
    </details>

    <details class="faq-item">
      <summary class="faq-q">Les montants annoncés sur cette page sont-ils garantis ?<span class="plus"></span></summary>
      <div class="faq-a">Non — ce sont les conditions communiquées par Hello bank! au moment où j'ai écrit cette page, et elles peuvent changer. Je vous confirmerai le montant exact en vigueur au moment de l'invitation, et vous pouvez toujours vérifier les conditions à jour sur hellobank.fr.</div>
    </details>

  </section>
</div>

<div class="wrap">
  <footer>
    <div class="footer-grid">

      <div class="footer-brand">
        <div class="brand">
          <span class="brand-mark"><span class="brand-dot"></span></span>
          <span>Hello bank! — Parrainage</span>
        </div>
        <p>Une page tenue par un client Hello bank!, pour partager son offre de parrainage avec ses proches. Ce n'est pas un site officiel Hello bank! ou BNP Paribas.</p>
      </div>

      <div class="footer-col">
        <div class="footer-title">Naviguer</div>
        <a href="#comment-ca-marche">Comment ça marche</a>
        <a href="#form">Demander une invitation</a>
        <a href="#prime">Les primes</a>
        <a href="#faq">Questions fréquentes</a>
      </div>

      <div class="footer-col">
        <div class="footer-title">Me contacter</div>
        <a href="mailto:parrainnageaide@gmail.com">parrainnageaide@gmail.com</a>
        <a href="https://www.hellobank.fr" target="_blank" rel="noopener">Site officiel hellobank.fr</a>
      </div>

    </div>

    <p class="footer-legal">
      * Montants communiqués par Hello bank!, informations à jour au 17/09/2026 et données à titre indicatif : jusqu'à 140 € pour le parrain par filleul validé, dans la limite de 10 filleuls par année civile ; jusqu'à 280 € pour le filleul (80 € de prime de bienvenue + jusqu'à 200 € de bon d'achat Hello Start+ en cas de mobilité bancaire, non systématique). Offre soumise à conditions d'éligibilité (majorité, résidence fiscale en France, absence de compte Hello bank! préalable) et à un délai de conservation minimum du compte d'un an. Les montants et délais exacts en vigueur sont à vérifier sur <a href="https://www.hellobank.fr" target="_blank" rel="noopener">hellobank.fr</a>.
    </p>
  </footer>
</div>

</div>

<style>

@import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@500;600;700&family=Inter:wght@400;500;600;700&display=swap');

#hb-page {
  --bg: #070B12;
  --bg-alt: #0A0F18;
  --panel: rgba(255,255,255,0.035);
  --panel-solid: #0E1520;
  --panel-border: rgba(255,255,255,0.09);
  --ink: #F3F8F8;
  --ink-soft: #93AAB0;
  --ink-faint: #57696F;
  --turquoise: #22E6C6;
  --turquoise-deep: #0FA98F;
  --turquoise-glow: rgba(34,230,198,0.16);
  --amber: #FFB648;
  --line: rgba(255,255,255,0.09);
  --radius-s: 8px;
  --radius-m: 16px;
  --radius-l: 28px;
  --font-display: "Space Grotesk", "Helvetica Neue", Arial, sans-serif;
  --font-body: "Inter", -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;

  box-sizing: border-box;
  background: var(--bg);
  color: var(--ink);
  font-family: var(--font-body);
  font-size: 16px;
  line-height: 1.6;
  -webkit-font-smoothing: antialiased;
  width: 100%;
  position: relative;
  overflow-x: hidden;
}

#hb-page *,
#hb-page *::before,
#hb-page *::after { box-sizing: border-box; }

#hb-page img, #hb-page svg { max-width: 100%; }

#hb-page :focus-visible {
  outline: 2px solid var(--turquoise);
  outline-offset: 2px;
}

#hb-page .grain {
  position: absolute;
  inset: 0;
  pointer-events: none;
  background:
    radial-gradient(ellipse 900px 500px at 15% -5%, var(--turquoise-glow), transparent 60%),
    radial-gradient(ellipse 700px 500px at 100% 15%, rgba(255,182,72,0.08), transparent 55%);
  z-index: 0;
}

#hb-page .wrap {
  max-width: 1100px;
  margin: 0 auto;
  padding: 0 24px;
  position: relative;
  z-index: 1;
}

#hb-page a { color: var(--turquoise); text-decoration: none; }

#hb-page h1, #hb-page h2, #hb-page h3 {
  font-family: var(--font-display);
  font-weight: 600;
  line-height: 1.15;
  margin: 0;
  color: var(--ink);
  letter-spacing: -0.01em;
}

#hb-page p { margin: 0 0 1em; color: var(--ink-soft); }
#hb-page p:last-child { margin-bottom: 0; }

#hb-page .num { color: var(--amber); font-variant-numeric: tabular-nums; }

#hb-page header.site {
  padding: 20px 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
  position: sticky;
  top: 0;
  z-index: 20;
  background: rgba(7,11,18,0.72);
  backdrop-filter: blur(14px);
  -webkit-backdrop-filter: blur(14px);
  margin: 0 -24px;
  padding-left: 24px;
  padding-right: 24px;
  border-bottom: 1px solid transparent;
}

#hb-page .brand {
  display: flex;
  align-items: center;
  gap: 10px;
  font-family: var(--font-display);
  font-size: 16px;
  font-weight: 600;
  color: var(--ink);
}

#hb-page .brand-mark {
  width: 30px;
  height: 30px;
  border-radius: 50%;
  border: 1.5px solid var(--turquoise);
  display: flex;
  align-items: center;
  justify-content: center;
  flex-shrink: 0;
}

#hb-page .brand-dot {
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background: var(--turquoise);
  box-shadow: 0 0 10px var(--turquoise);
}

#hb-page nav.site { display: flex; align-items: center; }

#hb-page nav.site a {
  color: var(--ink-soft);
  font-size: 14.5px;
  margin-left: 26px;
  font-weight: 500;
}

#hb-page nav.site a:hover { color: var(--ink); }

#hb-page .btn-nav {
  background: var(--turquoise);
  color: #04231D !important;
  padding: 9px 18px;
  border-radius: 999px;
  margin-left: 26px;
  font-weight: 600;
}

#hb-page .btn {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  font-family: var(--font-body);
  font-weight: 600;
  font-size: 15px;
  padding: 13px 22px;
  border-radius: 999px;
  text-decoration: none;
  border: 1px solid transparent;
  cursor: pointer;
}

#hb-page .btn-primary {
  background: linear-gradient(135deg, var(--turquoise), var(--turquoise-deep));
  color: #04231D;
}
#hb-page .btn-primary:hover { filter: brightness(1.08); }

#hb-page .btn-ghost {
  background: transparent;
  color: var(--ink);
  border-color: var(--line);
}
#hb-page .btn-ghost:hover { border-color: var(--turquoise); color: var(--turquoise); }

#hb-page .btn-block { width: 100%; justify-content: center; }

#hb-page .link-arrow {
  font-weight: 600;
  font-size: 14.5px;
  border-bottom: 1px solid var(--turquoise-deep);
  padding-bottom: 2px;
}

#hb-page .hero { padding: 56px 0 88px; }

#hb-page .hero-grid {
  display: grid;
  grid-template-columns: 1.1fr 0.9fr;
  gap: 56px;
  align-items: center;
}

#hb-page .kicker {
  font-size: 14px;
  color: var(--turquoise);
  font-weight: 600;
  margin-bottom: 14px;
}

#hb-page .hero h1 {
  font-size: clamp(32px, 4.2vw, 48px);
}

#hb-page .hero .lede {
  font-size: 17.5px;
  margin-top: 18px;
  max-width: 46ch;
}

#hb-page .hero-ctas {
  display: flex;
  gap: 12px;
  margin-top: 30px;
  flex-wrap: wrap;
}

#hb-page .hero-orbit {
  position: relative;
  height: 340px;
}

#hb-page .orbit-ring {
  position: absolute;
  border: 1px dashed rgba(34,230,198,0.25);
  border-radius: 50%;
  top: 50%;
  left: 46%;
}
#hb-page .ring-a { width: 300px; height: 300px; margin: -150px 0 0 -150px; }
#hb-page .ring-b { width: 400px; height: 400px; margin: -200px 0 0 -200px; border-color: rgba(255,182,72,0.16); }

#hb-page .orbit-dot {
  position: absolute;
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background: var(--amber);
  box-shadow: 0 0 12px var(--amber);
  top: 50%;
  left: 46%;
  margin: -150px 0 0 -4px;
  transform-origin: 4px 150px;
  animation: orbit 14s linear infinite;
}
@keyframes orbit { to { transform: rotate(360deg); } }

#hb-page .node-card {
  background: var(--panel-solid);
  border: 1px solid var(--panel-border);
  border-radius: var(--radius-m);
  padding: 18px 20px;
  position: absolute;
  backdrop-filter: blur(6px);
}

#hb-page .node-you { top: 18px; left: 0; }
#hb-page .node-friend {
  bottom: 18px;
  right: 0;
  border-color: rgba(34,230,198,0.4);
  box-shadow: 0 0 0 1px rgba(34,230,198,0.15), 0 20px 40px -20px rgba(34,230,198,0.35);
}

#hb-page .node-label { font-size: 12.5px; color: var(--ink-faint); margin-bottom: 4px; }
#hb-page .node-amount { font-family: var(--font-display); font-size: 25px; color: var(--ink); }
#hb-page .node-amount sup { font-size: 13px; color: var(--ink-faint); }

#hb-page section { padding: 60px 0; border-top: 1px solid var(--line); }
#hb-page .eyebrow-free h2 { font-size: clamp(24px, 3vw, 32px); margin-bottom: 14px; }
#hb-page .section-head { max-width: 62ch; margin-bottom: 40px; }

#hb-page .steps { display: grid; gap: 0; }

#hb-page .step {
  display: grid;
  grid-template-columns: 40px 1fr;
  gap: 18px;
  padding: 20px 0;
  border-top: 1px solid var(--line);
}
#hb-page .step:first-child { border-top: none; }

#hb-page .step-num {
  width: 32px;
  height: 32px;
  border-radius: 50%;
  border: 1px solid var(--panel-border);
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: var(--font-display);
  font-size: 13px;
  color: var(--turquoise);
  background: var(--panel);
}

#hb-page .step h3 { font-size: 17px; font-weight: 600; font-family: var(--font-body); margin-bottom: 4px; color: var(--ink); }
#hb-page .step p { font-size: 15px; }
#hb-page .steps-cta { margin-top: 30px; }

#hb-page .form-panel {
  background: var(--panel);
  border: 1px solid var(--panel-border);
  border-radius: var(--radius-l);
  padding: 34px;
  backdrop-filter: blur(6px);
}

#hb-page .field { margin-bottom: 16px; }
#hb-page .field label { display: block; font-size: 13px; font-weight: 600; color: var(--ink-soft); margin-bottom: 6px; }
#hb-page .field .optional { font-weight: 400; color: var(--ink-faint); }

#hb-page .field input {
  width: 100%;
  padding: 12px 14px;
  border-radius: var(--radius-s);
  border: 1px solid var(--panel-border);
  background: var(--bg-alt);
  color: var(--ink);
  font-family: var(--font-body);
  font-size: 15px;
}
#hb-page .field input::placeholder { color: var(--ink-faint); }
#hb-page .field input:focus { outline: 2px solid var(--turquoise); outline-offset: 1px; }
#hb-page .field-row { display: grid; grid-template-columns: 1fr 1fr; gap: 14px; }

#hb-page .form-note { font-size: 12.5px; color: var(--ink-faint); margin-top: 14px; }

#hb-page #confirm-msg {
  display: none;
  background: rgba(34,230,198,0.08);
  border: 1px solid rgba(34,230,198,0.3);
  border-radius: var(--radius-s);
  padding: 14px 16px;
  font-size: 14px;
  margin-top: 16px;
  color: var(--ink);
}
#hb-page #confirm-msg.is-error {
  background: rgba(255,182,72,0.08);
  border-color: rgba(255,182,72,0.35);
}
#hb-page #confirm-msg a { font-weight: 600; }

#hb-page .btn[disabled] { opacity: 0.6; cursor: default; }

#hb-page .prime-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 22px; }

#hb-page .prime-card {
  background: var(--panel);
  border: 1px solid var(--panel-border);
  border-radius: var(--radius-l);
  padding: 30px 28px;
}

#hb-page .prime-card-featured {
  border-color: rgba(34,230,198,0.4);
  box-shadow: 0 0 0 1px rgba(34,230,198,0.12), 0 30px 60px -30px rgba(34,230,198,0.35);
  background: linear-gradient(180deg, rgba(34,230,198,0.06), rgba(34,230,198,0.01));
}

#hb-page .prime-card .who { font-size: 13px; color: var(--ink-faint); margin-bottom: 6px; }
#hb-page .prime-card .amount { font-family: var(--font-display); font-size: 38px; margin-bottom: 12px; color: var(--ink); }
#hb-page .prime-card ul { margin: 14px 0 0; padding-left: 18px; }
#hb-page .prime-card li { font-size: 14.5px; color: var(--ink-soft); margin-bottom: 8px; }

#hb-page .total-block {
  background: linear-gradient(135deg, #0C2622, #081B18);
  border: 1px solid rgba(34,230,198,0.25);
  border-radius: var(--radius-l);
  padding: 40px 36px;
  display: grid;
  grid-template-columns: 1fr auto;
  gap: 24px;
  align-items: center;
}

#hb-page .total-block h3 { color: var(--ink); font-size: 19px; margin-bottom: 10px; font-weight: 600; font-family: var(--font-body); }
#hb-page .total-block p { color: var(--ink-soft); font-size: 14.5px; }
#hb-page .num-wrap { text-align: right; }
#hb-page .num-big { font-family: var(--font-display); font-size: clamp(38px,5.6vw,58px); color: var(--amber); line-height: 1; }
#hb-page .num-cap { font-size: 13px; color: var(--ink-faint); margin-top: 6px; }

#hb-page .helper-box,
#hb-page .contact-box {
  display: grid;
  grid-template-columns: auto 1fr auto;
  align-items: center;
  gap: 22px;
  background: var(--panel);
  border: 1px solid var(--panel-border);
  border-radius: var(--radius-l);
  padding: 30px;
}

#hb-page .helper-box { grid-template-columns: auto 1fr; }

#hb-page .helper-icon,
#hb-page .contact-icon {
  width: 46px;
  height: 46px;
  border-radius: 50%;
  background: var(--turquoise-glow);
  border: 1px solid rgba(34,230,198,0.35);
  display: flex;
  align-items: center;
  justify-content: center;
  flex-shrink: 0;
  font-size: 19px;
}

#hb-page .helper-copy h3,
#hb-page .contact-box h3 { font-size: 17px; font-weight: 600; font-family: var(--font-body); margin-bottom: 6px; color: var(--ink); }
#hb-page .helper-copy p,
#hb-page .contact-box p { font-size: 14.5px; margin: 0 0 14px; }
#hb-page .helper-copy .btn { margin-top: 4px; }

#hb-page .faq-item { border-top: 1px solid var(--line); }
#hb-page .faq-item:last-child { border-bottom: 1px solid var(--line); }

#hb-page .faq-q {
  width: 100%;
  text-align: left;
  background: none;
  border: none;
  cursor: pointer;
  padding: 18px 0;
  font-family: var(--font-body);
  font-weight: 600;
  font-size: 15.5px;
  color: var(--ink);
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 16px;
}

#hb-page .faq-q .plus { flex-shrink: 0; width: 22px; height: 22px; position: relative; }
#hb-page .faq-q .plus::before,
#hb-page .faq-q .plus::after {
  content: "";
  position: absolute;
  background: var(--ink-soft);
  top: 50%; left: 50%;
  transform: translate(-50%,-50%);
  transition: transform .2s ease;
}
#hb-page .faq-q .plus::before { width: 14px; height: 2px; }
#hb-page .faq-q .plus::after { width: 2px; height: 14px; }
#hb-page .faq-item[open] .plus::after { transform: translate(-50%,-50%) rotate(90deg) scale(0); }

#hb-page .faq-a { padding: 0 0 20px; font-size: 14.5px; max-width: 68ch; color: var(--ink-soft); }
#hb-page .faq-item summary { list-style: none; }
#hb-page .faq-item summary::-webkit-details-marker { display: none; }

#hb-page footer { border-top: 1px solid var(--line); padding: 50px 0 40px; }

#hb-page .footer-grid {
  display: grid;
  grid-template-columns: 1.4fr 1fr 1fr;
  gap: 40px;
  margin-bottom: 36px;
}

#hb-page .footer-brand p { font-size: 13.5px; margin-top: 14px; max-width: 34ch; }

#hb-page .footer-title { font-size: 12.5px; color: var(--ink-faint); font-weight: 600; margin-bottom: 12px; }
#hb-page .footer-col { display: flex; flex-direction: column; gap: 9px; }
#hb-page .footer-col a { color: var(--ink-soft); font-size: 14px; }
#hb-page .footer-col a:hover { color: var(--turquoise); }

#hb-page .footer-legal { font-size: 12px; color: var(--ink-faint); max-width: 90ch; border-top: 1px solid var(--line); padding-top: 24px; }
#hb-page .footer-legal a { color: var(--ink-faint); text-decoration: underline; }

@media (max-width: 820px) {
  #hb-page .hero-grid { grid-template-columns: 1fr; }
  #hb-page .hero-orbit { order: -1; height: 260px; max-width: 360px; margin: 0 auto; }
  #hb-page .prime-grid { grid-template-columns: 1fr; }
  #hb-page .total-block { grid-template-columns: 1fr; text-align: left; }
  #hb-page .num-wrap { text-align: left; }
  #hb-page .field-row { grid-template-columns: 1fr; }
  #hb-page .helper-box,
  #hb-page .contact-box { grid-template-columns: 1fr; text-align: left; }
  #hb-page .footer-grid { grid-template-columns: 1fr; gap: 28px; }
  #hb-page nav.site a:not(.btn-nav) { display: none; }
}

</style>

<script>
(function () {

  const root = document.getElementById('hb-page');
  if (!root) return;

  const FORM_ENDPOINT = "https://formspree.io/f/VOTRE_ID_FORMSPREE";

  const form = root.querySelector('#lead-form');
  const confirmBox = root.querySelector('#confirm-msg');
  const submitBtn = root.querySelector('#submit-btn');
  const btnLabel = submitBtn.querySelector('.btn-label');

  function showMessage(html, isError) {
    confirmBox.innerHTML = html;
    confirmBox.style.display = 'block';
    confirmBox.classList.toggle('is-error', !!isError);
  }

  form.addEventListener('submit', async function (e) {
    e.preventDefault();

    const prenom = root.querySelector('#prenom').value.trim();
    const nom = root.querySelector('#nom').value.trim();
    const email = root.querySelector('#email').value.trim();
    const telephone = root.querySelector('#telephone').value.trim();

    if (!prenom || !nom || !email) {
      showMessage('Merci de renseigner au moins votre prénom, votre nom et votre email.', true);
      return;
    }

    submitBtn.setAttribute('disabled', 'disabled');
    btnLabel.textContent = 'Envoi en cours…';

    const payload = {
      prenom: prenom,
      nom: nom,
      email: email,
      telephone: telephone,
      source: 'page-parrainage-hello-bank'
    };

    const configured = FORM_ENDPOINT.indexOf('VOTRE_ID_FORMSPREE') === -1;

    try {
      if (!configured) { throw new Error('endpoint-non-configure'); }

      const res = await fetch(FORM_ENDPOINT, {
        method: 'POST',
        headers: { 'Content-Type': 'application/json', 'Accept': 'application/json' },
        body: JSON.stringify(payload)
      });

      if (!res.ok) { throw new Error('reponse-serveur-' + res.status); }

      showMessage(
        'Merci ' + prenom + ', c\'est enregistré ! Je reviens vers vous par email avec l\'invitation officielle, généralement sous 24 à 48h.'
      );
      form.reset();

    } catch (err) {

      const mailto =
        'mailto:parrainnageaide@gmail.com' +
        '?subject=' + encodeURIComponent('Demande de parrainage Hello bank! — ' + prenom + ' ' + nom) +
        '&body=' + encodeURIComponent(
          'Bonjour,\n\nJe souhaite être parrainé(e) pour ouvrir un compte Hello bank!.\n\nPrénom : ' + prenom +
          '\nNom : ' + nom + '\nEmail : ' + email + '\nTéléphone : ' + (telephone || '—') +
          '\n\nMerci de m\'envoyer l\'invitation depuis votre espace client.'
        );

      showMessage(
        'La demande n\'a pas pu être enregistrée automatiquement. ' +
        '<a href="' + mailto + '">Cliquez ici pour me l\'envoyer par email</a>, ou écrivez directement à ' +
        '<a href="mailto:parrainnageaide@gmail.com">parrainnageaide@gmail.com</a>.',
        true
      );

    } finally {
      submitBtn.removeAttribute('disabled');
      btnLabel.textContent = 'Recevoir mon invitation';
    }

  });

})();
</script>
