Vul onderstaande aan met de antwoorden op de vragen uit de readme.md file. Wil je de oplossingen file van opmaak voorzien? Gebruik dan [deze link](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) om informatie te krijgen over
opmaak met Markdown.

a)
  eerst hebben we ervoor gezorgd dat de jenkins user de juiste rechten krijgt:
  ![docker_rights](/images/Changing_rights_docker.png)

  daanra hebben we docker credentials toegevoegd in jenkins:
  ![docker_rights](/images/Adding_docker_creds.png)

  Uiteindelijk krijgen we SUCCES terug na het runnen van de pipeline:
  ![test pipeline succes](/images/dtap_test_pipeline_succes.png)
  
b)
  curl succesvol bij het runnen van de pipeline:
  ![product_pipeline_curl_succes](/images/dtap_prod_pipeline_curl_succes.png)

  uiteindelijk krijgen we ook bij deze pipeline SUCCES terug:
  ![product_pipeline_succes](/images/dtap_prod_pipeline_succes.png)
