# VS Code

This is a quick guide to my VS Code Setup

## Settings

Enable these [settings](https://code.visualstudio.com/docs/getstarted/settings#_default-settings)

```json
{
  "editor.stickyScroll.enabled": true, # See https://www.youtube.com/watch?v=iM4Vhrk4irY
  "explorer.fileNesting.enabled": true, #See https://www.youtube.com/shorts/5kikdSqDm48
  "git.branchPrefix": "yourname/", # create git branches with your name as the prefix
}
```

## Git

Use VS Code as default git editor

```
[core]
  editor = code --wait
[diff]
  tool = vscode
[difftool "vscode"]
  cmd = code --wait --diff $LOCAL $REMOTE
[merge]
  tool = vscode
[mergetool "vscode"]
  cmd = code --wait $MERGED
```

## Extensions

These the extensions that I have installed. I don't use all of these extensively. Run the command to install it yourself if you like it.

code --install-extension [4ops.terraform](https://marketplace.visualstudio.com/items?itemName=4ops.terraform)
code --install-extension [aaron-bond.better-comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
code --install-extension [alefragnani.Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)
code --install-extension [amazonwebservices.aws-toolkit-vscode](https://marketplace.visualstudio.com/items?itemName=amazonwebservices.aws-toolkit-vscode)
code --install-extension [Angular.ng-template](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)
code --install-extension [atlassian.atlascode](https://marketplace.visualstudio.com/items?itemName=atlassian.atlascode)
code --install-extension [aws-scripting-guy.cform](https://marketplace.visualstudio.com/items?itemName=aws-scripting-guy.cform)
code --install-extension [bencoleman.armview](https://marketplace.visualstudio.com/items?itemName=bencoleman.armview)
code --install-extension [bibhasdn.unique-lines](https://marketplace.visualstudio.com/items?itemName=bibhasdn.unique-lines)
code --install-extension [bradlc.vscode-tailwindcss](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)
code --install-extension [bradymholt.pgformatter](https://marketplace.visualstudio.com/items?itemName=bradymholt.pgformatter)
code --install-extension [christian-kohler.npm-intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
code --install-extension [christian-kohler.path-intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
code --install-extension [Chukwuamaka.csvtojson-converter](https://marketplace.visualstudio.com/items?itemName=Chukwuamaka.csvtojson-converter)
code --install-extension [dannysteenman.cloudformation-yaml-snippets](https://marketplace.visualstudio.com/items?itemName=dannysteenman.cloudformation-yaml-snippets)
code --install-extension [dariofuzinato.vue-peek](https://marketplace.visualstudio.com/items?itemName=dariofuzinato.vue-peek)
code --install-extension [DavidAnson.vscode-markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
code --install-extension [dbaeumer.jshint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.jshint)
code --install-extension [dbaeumer.vscode-eslint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
code --install-extension [DotJoshJohnson.xml](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml)
code --install-extension [eamodio.gitlens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
code --install-extension [EditorConfig.EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
code --install-extension [esbenp.prettier-vscode](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
code --install-extension [firefox-devtools.vscode-firefox-debug](https://marketplace.visualstudio.com/items?itemName=firefox-devtools.vscode-firefox-debug)
code --install-extension [formulahendry.auto-close-tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
code --install-extension [formulahendry.auto-complete-tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-complete-tag)
code --install-extension [formulahendry.auto-rename-tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
code --install-extension [formulahendry.code-runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)
code --install-extension [formulahendry.dotnet-test-explorer](https://marketplace.visualstudio.com/items?itemName=formulahendry.dotnet-test-explorer)
code --install-extension [GrapeCity.gc-excelviewer](https://marketplace.visualstudio.com/items?itemName=GrapeCity.gc-excelviewer)
code --install-extension [hashicorp.terraform](https://marketplace.visualstudio.com/items?itemName=hashicorp.terraform)
code --install-extension [hbenl.vscode-test-explorer](https://marketplace.visualstudio.com/items?itemName=hbenl.vscode-test-explorer)
code --install-extension [hollowtree.vue-snippets](https://marketplace.visualstudio.com/items?itemName=hollowtree.vue-snippets)
code --install-extension [HookyQR.minify](https://marketplace.visualstudio.com/items?itemName=HookyQR.minify)
code --install-extension [humao.rest-client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)
code --install-extension [janisdd.vscode-edit-csv](https://marketplace.visualstudio.com/items?itemName=janisdd.vscode-edit-csv)
code --install-extension [jmrog.vscode-nuget-package-manager](https://marketplace.visualstudio.com/items?itemName=jmrog.vscode-nuget-package-manager)
code --install-extension [johnpapa.angular-essentials](https://marketplace.visualstudio.com/items?itemName=johnpapa.angular-essentials)
code --install-extension [johnpapa.Angular2](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2)
code --install-extension [johnpapa.vscode-peacock](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock)
code --install-extension [johnpapa.winteriscoming](https://marketplace.visualstudio.com/items?itemName=johnpapa.winteriscoming)
code --install-extension [jorgeserrano.vscode-csharp-snippets](https://marketplace.visualstudio.com/items?itemName=jorgeserrano.vscode-csharp-snippets)
code --install-extension [kddejong.vscode-cfn-lint](https://marketplace.visualstudio.com/items?itemName=kddejong.vscode-cfn-lint)
code --install-extension [markis.code-coverage](https://marketplace.visualstudio.com/items?itemName=markis.code-coverage)
code --install-extension [mechatroner.rainbow-csv](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)
code --install-extension [mhutchie.git-graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)
code --install-extension [Mikael.Angular-BeastCode](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode)
code --install-extension [mitchdenny.ecdc](https://marketplace.visualstudio.com/items?itemName=mitchdenny.ecdc)
code --install-extension [moalamri.inline-fold](https://marketplace.visualstudio.com/items?itemName=moalamri.inline-fold)
code --install-extension [mohd-akram.vscode-html-format](https://marketplace.visualstudio.com/items?itemName=mohd-akram.vscode-html-format)
code --install-extension [ms-azure-devops.azure-pipelines](https://marketplace.visualstudio.com/items?itemName=ms-azure-devops.azure-pipelines)
code --install-extension [ms-azuretools.azure-dev](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.azure-dev)
code --install-extension [ms-azuretools.vscode-apimanagement](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-apimanagement)
code --install-extension [ms-azuretools.vscode-azureappservice](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azureappservice)
code --install-extension [ms-azuretools.vscode-azurefunctions](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurefunctions)
code --install-extension [ms-azuretools.vscode-azureresourcegroups](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azureresourcegroups)
code --install-extension [ms-azuretools.vscode-azurestaticwebapps](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurestaticwebapps)
code --install-extension [ms-azuretools.vscode-azurestorage](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurestorage)
code --install-extension [ms-azuretools.vscode-azurevirtualmachines](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurevirtualmachines)
code --install-extension [ms-azuretools.vscode-bicep](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-bicep)
code --install-extension [ms-azuretools.vscode-cosmosdb](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-cosmosdb)
code --install-extension [ms-azuretools.vscode-docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
code --install-extension [ms-dotnettools.csharp](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)
code --install-extension [ms-dotnettools.vscode-dotnet-runtime](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.vscode-dotnet-runtime)
code --install-extension [ms-mssql.data-workspace-vscode](https://marketplace.visualstudio.com/items?itemName=ms-mssql.data-workspace-vscode)
code --install-extension [ms-mssql.mssql](https://marketplace.visualstudio.com/items?itemName=ms-mssql.mssql)
code --install-extension [ms-mssql.sql-bindings-vscode](https://marketplace.visualstudio.com/items?itemName=ms-mssql.sql-bindings-vscode)
code --install-extension [ms-mssql.sql-database-projects-vscode](https://marketplace.visualstudio.com/items?itemName=ms-mssql.sql-database-projects-vscode)
code --install-extension [ms-python.python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
code --install-extension [ms-python.vscode-pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance)
code --install-extension [ms-toolsai.jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
code --install-extension [ms-toolsai.jupyter-keymap](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter-keymap)
code --install-extension [ms-toolsai.jupyter-renderers](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter-renderers)
code --install-extension [ms-vscode-remote.remote-containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
code --install-extension [ms-vscode-remote.remote-ssh](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh)
code --install-extension [ms-vscode-remote.remote-ssh-edit](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh-edit)
code --install-extension [ms-vscode-remote.remote-wsl](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl)
code --install-extension [ms-vscode.azure-account](https://marketplace.visualstudio.com/items?itemName=ms-vscode.azure-account)
code --install-extension [ms-vscode.azurecli](https://marketplace.visualstudio.com/items?itemName=ms-vscode.azurecli)
code --install-extension [ms-vscode.hexeditor](https://marketplace.visualstudio.com/items?itemName=ms-vscode.hexeditor)
code --install-extension [ms-vscode.live-server](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server)
code --install-extension [ms-vscode.powershell](https://marketplace.visualstudio.com/items?itemName=ms-vscode.powershell)
code --install-extension [ms-vscode.test-adapter-converter](https://marketplace.visualstudio.com/items?itemName=ms-vscode.test-adapter-converter)
code --install-extension [ms-vscode.vscode-node-azure-pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-node-azure-pack)
code --install-extension [ms-vsliveshare.vsliveshare](https://marketplace.visualstudio.com/items?itemName=ms-vsliveshare.vsliveshare)
code --install-extension [ms-vsliveshare.vsliveshare-audio](https://marketplace.visualstudio.com/items?itemName=ms-vsliveshare.vsliveshare-audio)
code --install-extension [ms-vsliveshare.vsliveshare-pack](https://marketplace.visualstudio.com/items?itemName=ms-vsliveshare.vsliveshare-pack)
code --install-extension [msazurermtools.azurerm-vscode-tools](https://marketplace.visualstudio.com/items?itemName=msazurermtools.azurerm-vscode-tools)
code --install-extension [mubaidr.vuejs-extension-pack](https://marketplace.visualstudio.com/items?itemName=mubaidr.vuejs-extension-pack)
code --install-extension [natewallace.angular2-inline](https://marketplace.visualstudio.com/items?itemName=natewallace.angular2-inline)
code --install-extension [nicollasr.vscode-streamdeck](https://marketplace.visualstudio.com/items?itemName=nicollasr.vscode-streamdeck)
code --install-extension [nrwl.angular-console](https://marketplace.visualstudio.com/items?itemName=nrwl.angular-console)
code --install-extension [octref.vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
code --install-extension [oderwat.indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)
code --install-extension [patcx.vscode-nuget-gallery](https://marketplace.visualstudio.com/items?itemName=patcx.vscode-nuget-gallery)
code --install-extension [paulshestakov.aws-step-functions-constructor](https://marketplace.visualstudio.com/items?itemName=paulshestakov.aws-step-functions-constructor)
code --install-extension [PKief.material-icon-theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
code --install-extension [pnp.polacode](https://marketplace.visualstudio.com/items?itemName=pnp.polacode)
code --install-extension [pranaygp.vscode-css-peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)
code --install-extension [RapidAPI.vscode-rapidapi-client](https://marketplace.visualstudio.com/items?itemName=RapidAPI.vscode-rapidapi-client)
code --install-extension [redhat.vscode-yaml](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)
code --install-extension [ritwickdey.LiveServer](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
code --install-extension [rust-lang.rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)
code --install-extension [ryanluker.vscode-coverage-gutters](https://marketplace.visualstudio.com/items?itemName=ryanluker.vscode-coverage-gutters)
code --install-extension [sdras.vue-vscode-snippets](https://marketplace.visualstudio.com/items?itemName=sdras.vue-vscode-snippets)
code --install-extension [streetsidesoftware.code-spell-checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
code --install-extension [stylelint.vscode-stylelint](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint)
code --install-extension [thekalinga.bootstrap4-vscode](https://marketplace.visualstudio.com/items?itemName=thekalinga.bootstrap4-vscode)
code --install-extension [tombonnike.vscode-status-bar-format-toggle](https://marketplace.visualstudio.com/items?itemName=tombonnike.vscode-status-bar-format-toggle)
code --install-extension [usernamehw.errorlens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)
code --install-extension [vector-of-bool.gitflow](https://marketplace.visualstudio.com/items?itemName=vector-of-bool.gitflow)
code --install-extension [VisualStudioExptTeam.vscodeintellicode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)
code --install-extension [vivaxy.vscode-conventional-commits](https://marketplace.visualstudio.com/items?itemName=vivaxy.vscode-conventional-commits)
code --install-extension [vsciot-vscode.azure-iot-toolkit](https://marketplace.visualstudio.com/items?itemName=vsciot-vscode.azure-iot-toolkit)
code --install-extension [vscode-icons-team.vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
code --install-extension [Vue.volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar)
code --install-extension [xabikos.JavaScriptSnippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)
code --install-extension [yzhang.markdown-all-in-one](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
code --install-extension [zhuangtongfa.material-theme](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.material-theme)
code --install-extension [Zignd.html-css-class-completion](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)
