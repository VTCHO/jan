# Jan - Assistant IA local 

![Jan banner](./JanBanner.png)

<p align="center">
  <!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
  <img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/m/janhq/jan"/>
  <img alt="Github Last Commit" src="https://img.shields.io/github/last-commit/janhq/jan"/>
  <img alt="Github Contributors" src="https://img.shields.io/github/contributors/janhq/jan"/>
  <img alt="GitHub closed issues" src="https://img.shields.io/github/issues-closed/janhq/jan"/>
  <img alt="Discord" src="https://img.shields.io/discord/1107178041848909847?label=discord"/>
</p>

<p align="center">
  <a href="https://jan.ai/docs/quickstart">Getting Started</a> 
  - <a href="https://jan.ai/docs">Docs</a> 
  - <a href="https://github.com/janhq/jan/releases">Changelog</a> 
  - <a href="https://github.com/janhq/jan/issues">Bug reports</a> 
  - <a href="https://discord.gg/AsJ8krTT3N">Discord</a>
</p>

<p align="center">
⚠️ <b> Jan est actuellement en développement</b> : attendez-vous à des changements et à des bugs !
</p>


Jan est une alternative au ChatGPT qui fonctionne à 100 % hors ligne sur votre appareil. Notre objectif est de permettre à un profane de télécharger et d'exécuter des LLM et d'utiliser l'IA avec **un contrôle total** et **la confidentialité**.

Jan est alimenté par [Cortex](https://github.com/janhq/cortex.cpp), notre moteur d'IA locale intégrable qui fonctionne sur n'importe quel matériel.
Des PC aux clusters multi-GPU, Jan & Cortex prend en charge des architectures universelles :
- [x] NVIDIA GPUs (fast)
- [x] Apple M-series (fast)
- [x] Apple Intel
- [x] Linux Debian
- [x] Windows x64

#### Caractéristiques :
- [Bibliothèque des modèles](https://jan.ai/docs/models/manage-models#add-models) avec des LLM populaires comme Llama, Gemma, Mistral ou Qwen
- Se connecter aux  [Remote AI APIs](https://jan.ai/docs/remote-models/openai) comme Groq et OpenRouter
- Serveur API local avec API équivalente à l'OpenAI
- [Extensions](https://jan.ai/docs/extensions) pour personnaliser Jan
## Télécharger

<table>
  <tr style="text-align:center">
    <td style="text-align:center"><b>Version Type</b></td>
    <td style="text-align:center"><b>Windows</b></td>
    <td style="text-align:center"><b>MacOS Universal</b></td>
    <td colspan="2" style="text-align:center"><b>Linux</b></td>
  </tr>
  <tr style="text-align:center">
    <td style="text-align:center"><b>Stable (Recommandé)</b></td>
    <td style="text-align:center">
      <a href='https://app.jan.ai/download/latest/win-x64'>
        <img src='https://github.com/janhq/jan/blob/dev/docs/static/img/windows.png' style="height:14px; width: 14px" />
        <b>jan.exe</b>
      </a>
    </td>
    <td style="text-align:center">
      <a href='https://app.jan.ai/download/latest/mac-universal'>
        <img src='https://github.com/janhq/jan/blob/dev/docs/static/img/mac.png' style="height:15px; width: 15px" />
        <b>jan.dmg</b>
      </a>
    </td>
    <td style="text-align:center">
      <a href='https://app.jan.ai/download/latest/linux-amd64-deb'>
        <img src='https://github.com/janhq/jan/blob/dev/docs/static/img/linux.png' style="height:14px; width: 14px" />
        <b>jan.deb</b>
      </a>
    </td>
    <td style="text-align:center">
      <a href='https://app.jan.ai/download/latest/linux-amd64-appimage'>
        <img src='https://github.com/janhq/jan/blob/dev/docs/static/img/linux.png' style="height:14px; width: 14px" />
        <b>jan.AppImage</b>
      </a>
    </td>
  </tr>
  <tr style="text-align:center">
    <td style="text-align:center"><b>Beta (Preview)</b></td>
    <td style="text-align:center">
      <a href='https://app.jan.ai/download/beta/win-x64'>
        <img src='https://github.com/janhq/jan/blob/dev/docs/static/img/windows.png' style="height:14px; width: 14px" />
        <b>jan.exe</b>
      </a>
    </td>
    <td style="text-align:center">
      <a href='https://app.jan.ai/download/beta/mac-universal'>
        <img src='https://github.com/janhq/jan/blob/dev/docs/static/img/mac.png' style="height:15px; width: 15px" />
        <b>jan.dmg</b>
      </a>
    </td>
    <td style="text-align:center">
      <a href='https://app.jan.ai/download/beta/linux-amd64-deb'>
        <img src='https://github.com/janhq/jan/blob/dev/docs/static/img/linux.png' style="height:14px; width: 14px" />
        <b>jan.deb</b>
      </a>
    </td>
    <td style="text-align:center">
      <a href='https://app.jan.ai/download/beta/linux-amd64-appimage'>
        <img src='https://github.com/janhq/jan/blob/dev/docs/static/img/linux.png' style="height:14px; width: 14px" />
        <b>jan.AppImage</b>
      </a>
    </td>
  </tr>
  <tr style="text-align:center">
    <td style="text-align:center"><b>Nightly Build (Expérimental)</b></td>
    <td style="text-align:center">
      <a href='https://app.jan.ai/download/nightly/win-x64'>
        <img src='https://github.com/janhq/jan/blob/dev/docs/static/img/windows.png' style="height:14px; width: 14px" />
        <b>jan.exe</b>
      </a>
    </td>
    <td style="text-align:center">
      <a href='https://app.jan.ai/download/nightly/mac-universal'>
        <img src='https://github.com/janhq/jan/blob/dev/docs/static/img/mac.png' style="height:15px; width: 15px" />
        <b>jan.dmg</b>
      </a>
    </td>
    <td style="text-align:center">
      <a href='https://app.jan.ai/download/nightly/linux-amd64-deb'>
        <img src='https://github.com/janhq/jan/blob/dev/docs/static/img/linux.png' style="height:14px; width: 14px" />
        <b>jan.deb</b>
      </a>
    </td>
    <td style="text-align:center">
      <a href='https://app.jan.ai/download/nightly/linux-amd64-appimage'>
        <img src='https://github.com/janhq/jan/blob/dev/docs/static/img/linux.png' style="height:14px; width: 14px" />
        <b>jan.AppImage</b>
      </a>
    </td>
  </tr>
</table>

Téléchargez la dernière version de Jan à l'adresse suivante https://jan.ai/ ou visitez le site [GitHub Releases](https://github.com/janhq/jan/releases) pour télécharger toute version antérieure.

## Demo

https://github.com/user-attachments/assets/c3592fa2-c504-4d9d-a885-7e00122a50f3

*Real-time Video: Jan v0.5.7 on a Mac M2, 16GB Sonoma 14.2*

## Liens rapides

### Jan

- [Jan Website](https://jan.ai/)
- [Jan GitHub](https://github.com/janhq/jan)
- [Documentation](https://jan.ai/docs)
- [Jan Changelog](https://jan.ai/changelog)
- [Jan Blog](https://jan.ai/blog)

### Cortex.cpp
Jan est alimenté par **Cortex.cpp**. Il s'agit d'une interface de ligne de commande (CLI) en C++ conçue comme une alternative à [Ollama](https://ollama.com/). Par défaut, elle fonctionne sur le moteur llama.cpp mais supporte également d'autres moteurs, dont ONNX et TensorRT-LLM, ce qui en fait une plateforme multi-moteurs.


- [Cortex Website](https://cortex.so/)
- [Cortex GitHub](https://github.com/janhq/cortex.cpp)
- [Documentation](https://cortex.so/docs/)
- [Models Library](https://cortex.so/models)
- Référence API : *En cours de développement*
  
## Conditions requises pour l'exécution de Jan

- **MacOS**: 13 ou plus
- **Windows**:
  - Windows 10 ou supérieur
  - Pour activer la prise en charge du GPU :
  - GPU Nvidia avec CUDA Toolkit 11.7 ou supérieur
  - Pilote Nvidia 470.63.01 ou supérieur
  - **Linux** :
  -  glibc 2.27 ou supérieur (vérifiez avec `ldd --version`)
  -  gcc 11, g++ 11, cpp 11 ou supérieur, référez-vous à ce [lien](https://jan.ai/guides/troubleshooting/gpu-not-used/#specific-requirements-for-linux) pour plus d'informations
  -  Pour activer le support du GPU :
  -  GPU Nvidia avec CUDA Toolkit 11.7 ou supérieur
  -  Pilote Nvidia 470.63.01 ou supérieur




## Dépannage

Jan étant en mode développement, il se peut que vous soyez confronté à des problèmes courants :
- [Troubleshooting a broken build](https://jan.ai/docs/troubleshooting#broken-build)
- [Troubleshooting NVIDIA GPU](https://jan.ai/docs/troubleshooting#troubleshooting-nvidia-gpu)
- [Troubleshooting Something's Amiss](https://jan.ai/docs/troubleshooting#somethings-amiss)


Si vous ne trouvez pas ce dont vous avez besoin dans notre guide de dépannage, n'hésitez pas à nous contacter pour obtenir de l'aide supplémentaire :
1. Copiez vos [journaux d'erreurs et spécifications de l'appareil](https://jan.ai/docs/troubleshooting#how-to-get-error-logs).
2. Allez sur notre [Discord](https://discord.com/invite/FTk2MvZwJH) et envoyez-le dans le canal **#🆘|get-help** pour obtenir de l'aide.
*Vérifiez les journaux pour vous assurer que les informations correspondent à ce que vous avez l'intention d'envoyer. Notez que nous ne conservons vos journaux que pendant 24 heures, alors signalez-nous rapidement tout problème.*
  

## Contribuer

Les contributions sont les bienvenues ! Veuillez lire le fichier [CONTRIBUTING.md](CONTRIBUTING.md)
### Pré-requis

- node >= 20.0.0
- yarn >= 1.22.0
- make >= 3.81

### Instructions

1. **Cloner le référentiel et se préparer :**

   ```bash
   git clone https://github.com/janhq/jan
   cd jan
   git checkout -b DESIRED_BRANCH
   ```

2. **Lancer le développement et utiliser Jan Desktop**

   ```bash
   make dev
   ```

Cette opération permet de démarrer le serveur de développement et d'ouvrir l'application de bureau.


### Pour la production

```bash
# Do steps 1 and 2 in the previous section
# Build the app
make build
```

Ceci construira l'application MacOS m1/m2 pour la production (avec la signature du code déjà effectuée) et placera le résultat dans le dossier `dist`.

## Remerciements

Jan s'appuie sur d'autres projets open-source :

- [llama.cpp](https://github.com/ggerganov/llama.cpp)
- [LangChain](https://github.com/langchain-ai)
- [TensorRT](https://github.com/NVIDIA/TensorRT)
- [TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM)

## Contact

- Bugs et demandes : déposer un ticket GitHub
- Pour les discussions : rejoignez notre Discord [ici](https://discord.gg/FTk2MvZwJH)
- Pour les demandes de renseignements commerciaux : hello@jan.ai 
- Pour les offres d'emploi : veuillez envoyer un courriel à hr@jan.ai

## Confiance et sécurité

Attention aux escroqueries !

- Nous ne vous demanderons jamais d'informations personnelles.
- Notre produit est entièrement gratuit ; il n'existe pas de version payante.
- Nous n'avons pas de jeton ou d'ICO.
- Nous sommes une [quick-start company](https://en.wikipedia.org/wiki/Bootstrapping), et n'ont pas d'investisseurs extérieurs (*pour l'instant*). Nous sommes ouverts à l'exploration d'opportunités avec des partenaires stratégiques désireux de s'attaquer aux problèmes suivants [notre mission](https://jan.ai/about#mission) ensemble.

## Licence

Jan est libre et gratuit, sous la licence **AGPLv3**.
