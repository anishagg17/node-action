node-action #ActionsHackathon
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

This action checks each image in the commit to detects nudity and other inappropriate content in it.

Usage
See action.yml


` Works for node 8.x, 10.x, 12.x `
  
>  - uses: actions/checkout@v2
>   - name: Use Node.js ${{ matrix.node-version }}
>      uses: actions/setup-node@v1
>      with:
>        node-version: ${{ matrix.node-version }}
>    - run: npm install
>    - name: run loop
>      run: for filename in images/*; do node app.js "$filename" ; done


License
The scripts and documentation in this project are released under the MIT License


## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://anishagg17.github.io/my-portfolio/"><img src="https://avatars0.githubusercontent.com/u/43617894?v=4" width="100px;" alt=""/><br /><sub><b>Anish Aggarwal</b></sub></a><br /><a href="https://github.com/anishagg17/node-action/commits?author=anishagg17" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
