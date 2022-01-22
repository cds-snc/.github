# Security notice

This is the security notice for all Canadian Digital Service (CDS) repositories. The notice explains how vulnerabilities should be reported to CDS. At CDS there is a cyber security team, as well as security-conscious people within the organization, that assess and triage all reported vulnerabilities.

## How to report a vulnerability 
CDS is an advocate of responsible vulnerability disclosure. If you’ve found a vulnerability, we would like to know so we can fix it.

**You can report a vulnerability by sending an email to security+securite@cds-snc.ca**. You can submit reports anonymously. We do not support PGP-encrypted emails at this time.

### In your report:

- Write in English or French.
- Describe the vulnerability, where it was discovered, and the potential impact of exploitation.
- Offer a detailed description of the steps to reproduce the vulnerability (proof of concept scripts or screenshots are helpful). These should be benign, non-destructive, proofs of concept so we can triage your report quickly and accurately.
- Only submit reports about exploitable vulnerability
- Do not submit reports detailing non-exploitable vulnerabilities, or reports indicating that the services do not fully align with “best practice”. For example, missing security headers, or a high volume of low-quality reports (for example, from an automated scanner).
- Do not communicate any vulnerabilities or associated details other than by means described in this notice.
- Do not expect or demand financial compensation for your research and testing to disclose vulnerabilities.

You can still reach out via email at security+securite@cds-snc.ca if you are not sure if the vulnerability is genuine and exploitable, or you have found:
- A non-exploitable vulnerability.
- Something you think could be improved - for example, missing security headers.
- TLS configuration weaknesses - for example weak cipher suite support or the presence of TLS1.0 support.

### When you are investigating and reporting the vulnerability you must not:

- Break the law.
- Access unnecessary or excessive amounts of data.
- Modify data.
- Use high-intensity invasive or destructive scanning tools to find vulnerabilities.
- Try a denial of service - for example overwhelming a service on canada.ca with a high volume of requests.
- Disrupt Government of Canada’s services or systems.
- Tell other people about the vulnerability you have found until we have disclosed it.
- Social engineer, phish or physically attack our staff or infrastructure.
- Demand money to disclose a vulnerability.

## Code of Conduct
Please view our contributors code of conduct for more information on how to contribute in an open and welcoming way. 

## Bug bounty

Unfortunately, CDS doesn't offer a paid bug bounty program. CDS will make efforts to show appreciation to people who take the time and effort to disclose vulnerabilities responsibly. We do have an acknowledgements page for legitimate issues found by researchers.

## After you’ve reported the vulnerability

When you choose to share your contact information with us, we commit to communicating with you as openly and as quickly as possible.

- Within 3 business days, we will acknowledge that your report has been received.
- To the best of our ability, we will confirm the existence of the vulnerability to you and be as transparent as possible about what steps we are taking during the remediation process, including on issues or challenges that may delay resolution.
- We will prioritize fixing the vulnerability by looking at the impact, severity and exploit complexity. Vulnerability reports might take some time to triage or address. You’re welcome to ask the status but please no more than once every 14 days. That way, our teams can focus on the remediation.
- We will do our best to maintain an open dialogue with you to discuss issues and will work with you to determine whether and how the flaw reported will be made public.
- We will treat your report in accordance with the Access to Information Act and the Privacy Act.
- We will notify you when the reported vulnerability is remediated, and you may be invited to confirm that the solution covers the vulnerability adequately.

______________________

# Avis de sécurité
Voici l’avis de sécurité pour tous les référentiels de données du Service numérique canadien (SNC). Cet avis explique la procédure à suivre pour signaler toute vulnérabilité au SNC. Le SNC est doté d’une équipe de cybersécurité et d’employés soucieux de la sécurité, qui évaluent et traitent tout incident signalé.

## Comment signaler une vulnérabilité 
Le SNC est un défenseur de la divulgation responsable des vulnérabilités. Si vous avez repéré une vulnérabilité, nous aimerions le savoir afin de la corriger.
 
**Vous pouvez signaler une vulnérabilité en écrivant à security+securite@cds-snc.ca**. Vous pouvez également signaler un problème de manière anonyme. Pour l’instant, nous ne prenons pas en charge les courriels chiffrés avec clé PGP.

### Votre rapport de vulnérabilité :

- doit être rédigé en anglais ou en français;
- doit décrire la vulnérabilité, l’endroit où elle a été repérée et l’incidence potentielle de son exploitation;
- doit offrir une description détaillée des étapes permettant de reproduire la vulnérabilité (des scripts de démonstration ou des captures d’écran sont utiles). Ces preuves doivent être bénignes et non destructives, afin que nous puissions acheminer votre rapport rapidement et avec précision;
doit comporter seulement des renseignements sur des vulnérabilités exploitables;
- ne doit pas comporter de vulnérabilités non exploitables ou des signalements de services qui ne sont pas entièrement conformes aux « meilleures pratiques » (p. ex., des en-têtes de sécurité manquants ou un volume élevé de rapports de mauvaise qualité pouvant provenir d’un outil de diagnostic automatisé);
- ne doit communiquer aucune vulnérabilité ni aucun détail associé autre que par les moyens décrits dans cet avis;
- ne donnera lieu à aucune rémunération pour vos recherches et tests réalisés en vue de divulguer des vulnérabilités.

Vous pouvez toujours nous contacter par courriel à l’adresse security+securite@cds-snc.ca si vous n’êtes pas sûr que la vulnérabilité soit authentique et exploitable ou bien s’il s’agit :
- d’une vulnérabilité non exploitable;
- d’un élément quelconque qui peut être amélioré (p. ex., des en-têtes de sécurité manquants);
- d’une faille dans la configuration du protocole TLS (p. ex., une faible prise en charge des suites de chiffrement ou la prise en charge de la version 1.0 du protocole TLS).

## Lorsque vous examinez et signalez une vulnérabilité, vous ne devez pas :

- enfreindre la loi;
- accéder à des quantités inutiles ou excessives de données;
- modifier les données;
- utiliser d’outils d’analyse invasifs ou destructeurs de haute intensité pour trouver des vulnérabilités;
- tenter un déni de service (p. ex., saturer un service de canada.ca avec un volume élevé de demandes);
- perturber les services ou les systèmes du gouvernement du Canada;
- parler à quiconque de la vulnérabilité que vous avez trouvée jusqu’à ce que nous la divulguions;
- faire de l’ingénierie sociale, de l’hameçonnage ou attaquer physiquement notre personnel ou causer des dommages à notre infrastructure;
demander de l’argent en échange d’une divulgation.

## Code de conduite
Veuillez consulter le Code de conduite des contributeurs pour obtenir de plus amples renseignements sur la façon de contribuer de manière ouverte et accueillante. 
 
### Prime aux bogues
 
Malheureusement, le SNC n’offre pas de programme de prime aux bogues rémunéré, mais fera des efforts pour être reconnaissant envers les personnes qui prennent le temps et l’effort de divulguer des vulnérabilités de manière responsable. Nous disposons en fait d’une page de remerciements pour les problèmes légitimes découverts par les chercheurs.
 
## Après avoir signalé la vulnérabilité
 
 
Si vous choisissez de partager vos coordonnées avec nous, nous nous engageons à communiquer avec vous aussi ouvertement et rapidement que possible.

- Nous accuserons réception de votre rapport dans un délai de trois jours ouvrables.
- Dans la mesure du possible, nous vous confirmerons l’existence de la vulnérabilité et serons aussi transparents que possible sur les mesures que nous prenons au cours du processus de correction, ainsi que sur les problèmes ou les difficultés pouvant retarder la résolution.
- Nous donnerons priorité à la correction de la vulnérabilité en examinant l’incidence, la gravité et la complexité de l’exploitation. L’acheminement et le traitement des rapports de vulnérabilité peuvent prendre un certain temps. Nous vous renseignerons avec plaisir sur l’état de votre demande, mais seulement une fois tous les 14 jours. Nos équipes pourront ainsi se concentrer sur les mesures correctives.
- Nous ferons de notre mieux pour maintenir un dialogue ouvert avec vous afin de discuter des problèmes. Nous tâcherons également de déterminer avec vous de la pertinence de divulguer la faille et, le cas échéant, de la façon de le faire.
- Nous traiterons votre rapport conformément à la Loi sur l’accès à l’information et à la Loi sur la protection des renseignements personnels.
- Nous vous informerons lorsque la vulnérabilité signalée est corrigée. Vous pourriez aussi être invité à confirmer que la mesure corrige adéquatement la vulnérabilité.
 

