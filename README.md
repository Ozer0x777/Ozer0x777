<!--
  README de profil GitHub pour l'utilisateur ozer0x777.
  À placer dans le dépôt spécial https://github.com/Ozer0x777/ozer0x777 sous le nom README.md
  pour qu'il s'affiche en haut du profil.
  Les cartes de stats (github-readme-stats, streak-stats) se génèrent en direct côté service.
-->

<div align="center">

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=800&size=56&color=58A6FF&center=true&vCenter=true&repeat=false&width=700&height=90&lines=Ozer0x777" alt="Ozer0x777" />

**Malware Analyst · Reverse Engineer**

<br>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=18&color=58A6FF&center=true&vCenter=true&width=820&height=40&lines=%22Connect+it+to+the+internet+and+someone%27s+gonna+own+it%22" alt="quote" />

</div>

---

Analyste malware basé en France. Je remonte les chaînes d'infection de bout en bout, du dropper jusqu'aux exchanges crypto, en analyse **100% statique**, sans sandbox, sans exécution. Quand le décompilateur échoue, je lis les opcodes. Quand l'archive est corrompue, j'écris le codec. Quand les fonds sont traçables, je les trace jusqu'aux exchanges soumis au KYC et je rédige les signalements.

---

## Analyses publiées

<table>
<tr>
<td valign="top" width="50%">

### [Efimer](https://github.com/Ozer0x777/writeups/tree/master/efimer)
Dropper ClickFix + Clipper BTC/TRX/XMR + Botnet WP

- Contournement statique PyArmor 8.x (clé AES extraite sans exécution)
- Algorithme de nommage journalier reconstitué opcode par opcode
- Machine de build de l'attaquant identifiée via un module oublié dans le bundle
- Fonds tracés jusqu'à 2 exchanges KYC + FixedFloat

</td>
<td valign="top" width="50%">

### [AgentTesla](https://github.com/Ozer0x777/writeups/tree/master/agenttesla-netreactor-killchain)
Loader .NET + Infostealer

- Eziriz .NET Reactor : 1 891 cases de CFG, outils maison construits et validés
- Fausse piste d'auto-injection détectée et corrigée avant publication
- Config FTP exfil confirmée via recoupement sandbox indépendant

</td>
</tr>
<tr>
<td valign="top" width="50%">

### [StealC](https://github.com/Ozer0x777/writeups/tree/master/stealc-autoit-killchain)
Loader AutoIt + Infostealer MaaS

- IExpress + Asgard Protector : 354 blocs aplatis résolus, validés par 2 méthodes
- Process hollowing complet tracé via les APIs `Nt*`
- C2 actif confirmé sans s'y connecter

</td>
<td valign="top" width="50%">

### [Lazarus (DEV#POPPER)](https://github.com/Ozer0x777/writeups/tree/master/lazarus-githook)
Git hook + chaîne JS multi-stages + backdoor Python

- Hook git OS-aware, 3 stages JS obfuscator.io (rotation IIFE vérifiée, custom-b64)
- Dropper Cloudflare R2, backdoor Python stealer (Chrome/Brave/Edge)
- 3 IPs C2, persistance multi-OS, désobfuscateur dédié fourni

</td>
</tr>
<tr>
<td valign="top" width="50%">

### [wskmon](https://github.com/Ozer0x777/writeups/tree/master/wskmon-whql-backdoor)
Backdoor kernel signé WHQL (abus WFP)

- Driver x64 signé WHQL, backdoor réseau passif via Windows Filtering Platform
- Déclencheur 4 octets magiques + HMAC-SHA256, injection svchost SYSTEM
- 3 samples liés par un même certificat compromis, rapport MSRC de divulgation

</td>
<td valign="top" width="50%">

### [SaferRAT](https://github.com/Ozer0x777/writeups/tree/master/saferrat-android)
Banker Android (opérateur Diabloo)

- Overlay de phishing dynamique, VNC d'accessibilité, capture de PIN géolocalisée
- Exfiltration auto de la pellicule, 5 mécanismes de persistance distincts
- Attribution opérateur via tag codé en dur, version anglaise fournie

</td>
</tr>
<tr>
<td valign="top" width="50%">

### [InfernoGrabber](https://github.com/Ozer0x777/writeups/tree/master/deepseek-browser-ransomware)
Ransomware/stealer Python généré par DeepSeek (LLM)

- Serveur Flask monofichier, leurre « AI Discord Avatar Upscaler »
- Abus de la File System Access API (une autorisation = accès récursif complet)
- Commentaires russes, opérateur russophone relié via l'avatar Discord, règles YARA

</td>
<td valign="top" width="50%">

### [Tous les writeups →](https://github.com/Ozer0x777/writeups)
Le dépôt complet des analyses

- Un dossier par sujet, chacun autonome
- writeup + runbook + outils + IOCs
- Règles YARA et PoC de démonstration fournis

</td>
</tr>
</table>

---

## Projets

<table>
<tr>
<td valign="top" width="50%">

### [Heimdall](https://github.com/Ozer0x777/Heimdall)
Pipeline de triage malware

- 5 sandboxes en parallèle (VT, MalwareBazaar, Hybrid, JoeSandbox, Any.run)
- Export STIX 2.1 + intégration MISP
- Alertes Slack / Teams / Signal, quarantaine automatique

</td>
<td valign="top" width="50%">
</td>
</tr>
</table>

---

## Stack

![Python](https://img.shields.io/badge/PYTHON-3776AB?style=for-the-badge&logo=python&logoColor=white)
![YARA](https://img.shields.io/badge/YARA-EE7000?style=for-the-badge&logoColor=white)
![Ghidra](https://img.shields.io/badge/GHIDRA-CF3B36?style=for-the-badge&logoColor=white)
![IDA Free](https://img.shields.io/badge/IDA_FREE-5B2C8F?style=for-the-badge&logoColor=white)
![Linux](https://img.shields.io/badge/LINUX-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/GIT-F05032?style=for-the-badge&logo=git&logoColor=white)

![MalwareBazaar](https://img.shields.io/badge/MALWAREBAZAAR-2B2B2B?style=for-the-badge&logoColor=white)
![VirusTotal](https://img.shields.io/badge/VIRUSTOTAL-394EFF?style=for-the-badge&logo=virustotal&logoColor=white)
![MISP](https://img.shields.io/badge/MISP-1BA0E2?style=for-the-badge&logoColor=white)
![STIX 2.1](https://img.shields.io/badge/STIX_2.1-7A1E1E?style=for-the-badge&logoColor=white)
![Blockchain OSINT](https://img.shields.io/badge/BLOCKCHAIN_OSINT-E8A317?style=for-the-badge&logo=bitcoin&logoColor=white)

---

## Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=ozer0x777&show_icons=true&hide_border=true&theme=github_dark&count_private=true&icon_color=58A6FF&title_color=58A6FF" alt="stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ozer0x777&layout=compact&hide_border=true&theme=github_dark&title_color=58A6FF" alt="top langs" />

<br>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=ozer0x777&hide_border=true&theme=github-dark&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF" alt="streak" />

</div>

---

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gordon-p-04008517a/)
[![BlueTeamLabs](https://img.shields.io/badge/BLUETEAMLABS-0692D0?style=for-the-badge&logoColor=white)](https://blueteamlabs.online/home/user/ee1f34ae387c0178944493)
[![Writeups](https://img.shields.io/badge/WRITEUPS-24292E?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ozer0x777)

</div>
