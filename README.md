# Front-End Coding Guidelines

Installation Coding Guidelines For Front-End Developers.

## Getting started

Install dependencies:

``` bash
$ git clone git@github.com:niyg/hztCode.git
$ npm install
```

Generate:

``` bash
$ hexo g
```

Run server:

``` bash
$ hexo s --watch
```

## Deployment

1. Generate and optimize assets

  ```bash
  gulp
  ```

2. Deploy to the gh-pages branch

  ```bash
  hexo d -g
  ```
  发布时，如在站点的子目录底下。url设置成站点发布地址 ，root设置站点底下的文件目录（如开发环境上部署在ue/code/public）则root:ue/code/public/

## License

[CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)
