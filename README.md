# Tutorial of eLuvLetter usage
[![license](https://img.shields.io/github/license/Society-Genius/eLuvLetter.svg)](https://github.com/Society-Genius/eLuvLetter/blob/master/LICENSE)
[![Netlify Status](https://api.netlify.com/api/v1/badges/154babf2-94f7-4abf-a333-6f3e150dcf09/deploy-status)](https://eluvletter.netlify.app)
[![bilibili](https://img.shields.io/badge/bilibili-BV1NADfYCE1V-fc8bab.svg)](https://www.bilibili.com/video/BV1NADfYCE1V)
[![ms](https://img.shields.io/badge/ModelScope-eluvletter-624aff.svg)](https://www.modelscope.cn/studios/Genius-Society/eluvletter)
[![hf](https://img.shields.io/badge/HuggingFace-eluvletter-ffd21e.svg)](https://huggingface.co/spaces/Genius-Society/eluvletter)
[![cnblogs](https://img.shields.io/badge/cnblogs-16617269-075db3.svg)](https://www.cnblogs.com/Genius-Society/p/16617269.html)

The heartbeat animation indicates that the BGM is loading, please be patient and wait util the envelope appears.

## Customization
1. Download and install `Git`;
2. Register a `GitHub` account, set SSH, and fork a copy of this repository to your own account;
3. Clone the repository to local:
```bash
git clone git@github.com:%YOUR_GITHUB_USERNAME%/eLuvLetter.git
cd eLuvLetter
```

4. Customize `./font/content.json` by the [eLuvLetter JSON Generator](https://www.modelscope.cn/studios/Genius-Society/eluvletter);
5. Sync the modified local code to your `GitHub` account:
```bash
git add .
git commit -a
# press i
# input any description
# ESC :wq! Enter
git push
```

## Deployment on Netlify
1. Enter [Netlify](https://app.netlify.com) official website;
2. Use your GitHub account to login by authorization, click `Add new site` - `Import an existing project`;
3. Click `GitHub`, enter the keyword `eLuvLetter` in the search box to find the previously forked repo, and select it;
4. Click `Deploy site` to jump into `Site overview` page automatically, click `Site settings`;
5. Click `Change site name` under `Site information`, modify second-level domain name not conflict to others, and click `Save`;
6. After the deployment, we can visit `https://%PROJECT_NAME%.netlify.app` to broswe your page (`%PROJECT_NAME%` is the second-level domain name customized just now)

**Good luck~💖**
