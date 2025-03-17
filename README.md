<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

  <p align="center">A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.</p>
    <p align="center">
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/dm/@nestjs/common.svg" alt="NPM Downloads" /></a>
<a href="https://circleci.com/gh/nestjs/nest" target="_blank"><img src="https://img.shields.io/circleci/build/github/nestjs/nest/master" alt="CircleCI" /></a>
<a href="https://discord.gg/G7Qnnhy" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>
<a href="https://opencollective.com/nest#backer" target="_blank"><img src="https://opencollective.com/nest/backers/badge.svg" alt="Backers on Open Collective" /></a>
<a href="https://opencollective.com/nest#sponsor" target="_blank"><img src="https://opencollective.com/nest/sponsors/badge.svg" alt="Sponsors on Open Collective" /></a>
  <a href="https://paypal.me/kamilmysliwiec" target="_blank"><img src="https://img.shields.io/badge/Donate-PayPal-ff3f59.svg" alt="Donate us"/></a>
    <a href="https://opencollective.com/nest#sponsor"  target="_blank"><img src="https://img.shields.io/badge/Support%20us-Open%20Collective-41B883.svg" alt="Support us"></a>
  <a href="https://twitter.com/nestframework" target="_blank"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow" alt="Follow us on Twitter"></a>
</p>
  <!--[![Backers on Open Collective](https://opencollective.com/nest/backers/badge.svg)](https://opencollective.com/nest#backer)
  [![Sponsors on Open Collective](https://opencollective.com/nest/sponsors/badge.svg)](https://opencollective.com/nest#sponsor)-->

## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Project setup

```bash
$ npm install
```

## Compile and run the project

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Run tests

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Deployment

When you're ready to deploy your NestJS application to production, there are some key steps you can take to ensure it runs as efficiently as possible. Check out the [deployment documentation](https://docs.nestjs.com/deployment) for more information.

If you are looking for a cloud-based platform to deploy your NestJS application, check out [Mau](https://mau.nestjs.com), our official platform for deploying NestJS applications on AWS. Mau makes deployment straightforward and fast, requiring just a few simple steps:

```bash
$ npm install -g mau
$ mau deploy
```

With Mau, you can deploy your application in just a few clicks, allowing you to focus on building features rather than managing infrastructure.

## Resources

Check out a few resources that may come in handy when working with NestJS:

- Visit the [NestJS Documentation](https://docs.nestjs.com) to learn more about the framework.
- For questions and support, please visit our [Discord channel](https://discord.gg/G7Qnnhy).
- To dive deeper and get more hands-on experience, check out our official video [courses](https://courses.nestjs.com/).
- Deploy your application to AWS with the help of [NestJS Mau](https://mau.nestjs.com) in just a few clicks.
- Visualize your application graph and interact with the NestJS application in real-time using [NestJS Devtools](https://devtools.nestjs.com).
- Need help with your project (part-time to full-time)? Check out our official [enterprise support](https://enterprise.nestjs.com).
- To stay in the loop and get updates, follow us on [X](https://x.com/nestframework) and [LinkedIn](https://linkedin.com/company/nestjs).
- Looking for a job, or have a job to offer? Check out our official [Jobs board](https://jobs.nestjs.com).

## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## Stay in touch

- Author - [Kamil Myśliwiec](https://twitter.com/kammysliwiec)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)

## License

Nest is [MIT licensed](https://github.com/nestjs/nest/blob/master/LICENSE).

<!-- O=> -->
```bash
npm i -g @nestjs/cli
 8370  nest
 8371  nest -v
 8372  nest new sleepr
 8373  cd sleepr
 8374  ls
 8375  code .
 8376* npm run start
 505  git add .
  506  git commit -m "O=> initial commit"
  507  git push
  508  git remote add origin https://github.com/ronee-muhammad-rayhan/sleepr.git
  509  git push -u origin main
  510  nest generate library common
  511  history
  npm i @nestjs/mongoose mongoose
  pnpm i @nestjs/config
  nest generate module database -p common
  nest generate module config -p common


  485  git commit -m "test ci/cd"
  486  git push
  487  git checkout development 
  488  git status
  489  git add .
  490  git commit -m "modify env"
  491  git checkout development 
  492  npm run start"dev
  493  npm run start:dev
  494  git log
  495  git add .
  496  git commit -m "O=> Fix: Resolved GraphQL issues"
  497  git push origin main
  498  git branch -b main
  499  git branch -M main
  500  git push origin main
  501  git status
  502  git log
  503  ls -alt
  504  git remote -v
  505  git add .
  506  git commit -m "O=> initial commit"
  507  git push
  508  git remote add origin https://github.com/ronee-muhammad-rayhan/sleepr.git
  509  git push -u origin main
  510  nest generate library common
  511  history
  512  git add .
  513  git commit -m "generate common lib files"
  514  git push
  515  npm i @nestjs/mongoose mongoose
  516  npm i @nestjs/config
  517  nest generate module -p common
  518  nest generate module database -p common
  519  nest generate module config -p common
  520  git add .
  521  git status
  522  git commit -m "O=> database connected successfully"
  523  git push
  524  git reset --soft HEAD~1
  525  git status
  526  git restore --staged *
  527  git restore --staged data/db
  528  git status
  529  history
  530  git add .
  531  git commit -m "O=> database connected successfully"
  532  git push
  533  git pull origin main
  534  git config pull.ff only       # fast-forward only
  535  git push
  536  git pull origin main
  537  git config pull.rebase true   # rebase
  538  git pull origin main
  539  git config pull.rebase false  # merge
  540  git pull origin main
  541  git push
  542  git push --help
  543  git pull
  544  git fetch origin        # Fetch the latest changes from the remote
  545  git merge origin/main   # Replace 'main' with your branch name if different
  546  git pull origin main
  547  git status
  548  git status
  549  git restore data/
  550  git status
  551  git restore data/db
  552  git status
  553  git log
  554  git reflog
  555  git fetch origin
  556  git reset --hard origin/main
  557  git reflog
  558  git status
  559  git log
  560  git push
  561  git status
  562  git status
  563  git rm data/db/WiredTiger.turtle
  564  git rm data/db/WiredTiger.turtle --cached
  565  git status
  566  git rm data/ --cached
  567  git rm data/* --cached
  568  git rm data/db/sizeStorer.wt --cached
  569  git status
  570  git rm modified:   data/db/mongod.lock data/db/index-3--1243385440957942132.wt --cached
  571  git rm modified:   data/db/mongod.lock  --cached
  572  git rm  data/db/mongod.lock  --cached
  573  git rm  data/db/journal/WiredTigerLog.0000000001  --cached
  574  git status
  575  git rm  data/db/index-3--1243385440957942132.wt data/db/diagnostic.data/metrics.interim  --cached
  576  git rm  data/db/collection-2--1243385440957942132.wt  --cached
  577  git status
  578  git rm  data/db/WiredTiger.wt  --cached
  579  git add .
  580  git status
  581  git commit -m "delete large files"
  582  git push
  583  history

```