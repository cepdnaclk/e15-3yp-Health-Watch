# eYY-3yp-project-template

This is a sample repository you can use for your Embedded Systems project. Once you followed these instructions, remove the text and add a brief introduction to here.

### Enable GitHub Pages

You can put the things to be shown in GitHub pages into the _docs/_ folder. Both html and md file formats are supported. You need to go to settings and enable GitHub pages and select _main_ branch and _docs_ folder from the dropdowns, as shown in the below image.

![image](https://user-images.githubusercontent.com/11540782/98789936-028d3600-2429-11eb-84be-aaba665fdc75.png)

### Special Configurations

These projects will be automatically added into [https://projects.ce.pdn.ac.lk](). If you like to show more details about your project on this site, you can fill the parameters in the file, _/docs/index.json_

```
{
  "visibility": false,
  "title": "Health Watch",
  "team": [
    {
      "name": "K.N.U. Kularatne",
      "email": "e15188@eng.pdn.ac.lk",
      "eNumber": "E/15/188"
    },
    {
      "name": "S.C. Tennakoon",
      "email": "e15349@eng.pdn.ac.lk",
      "eNumber": "E/15/349"
    },
    {
      "name": "K.T.B. Weerasinghe",
      "email": "e15383@eng.pdn.ac.lk",
      "eNumber": "E/15/383"
    }
  ],
  "supervisors": [
    {
      "name": "Prof. Roshan G. Ragel",
      "email": "roshanr@eng.pdn.ac.lk"
    },
    {
      "name": "Dr. Isuru Nawinne",
      "email": "isurunawinne@eng.pdn.ac.lk"
    }
  ],
  "description": "Health Watch is a wrist band which monitors certain variables in the body, such as the heart rate, blood oxygen level and temperature.This product is mainly targeting the elderly people and those who need health monitoring on a daily basis. Not only does it monitor the health, it also maintains a database with the recorded measurements of the users (patients) and the data will be accessible by the people who look after them through a mobile and a web application. Health Watch will also indicate if the above measurements are beyond the standard rate.",
  "tags": ["Web", "Embedded Systems"]
}
```

Once you filled this _index.json_ file, please verify the syntax is correct. (You can use [this](https://jsonlint.com/) tool). Then change the _'visibility'_ property of the above json to _true_.

### Page Theme

A custom theme integrated with this GitHub Page, which is based on [github.com/cepdnaclk/eYY-project-theme](https://github.com/cepdnaclk/eYY-project-theme). If you like to remove this default theme, you can remove the file, _docs/\_config.yml_
