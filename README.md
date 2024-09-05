Formål
-------
Formålet med dette dokument er at introducere brugen af GitHub Actions, et automatiseringsværktøj, 
som giver udviklere mulighed for at opsætte automatiserede workflows, der udføres, når kode bliver checket ind i et GitHub repository. 
Dette kan inkludere opgaver som at kompilere kode, køre enhedstests, og deployere den færdige applikation til en cloud-tjeneste som Azure.

Udbytte af Øvelsen
-------------------
Ved at følge denne tutorial vil du opnå en grundlæggende forståelse af, 
hvordan man opretter og konfigurerer et GitHub Actions workflow. 
Du vil lære, hvordan man definerer jobs og actions inden for et workflow, 
og hvordan man kan bruge disse til at automatisere processer som kompilering og testning af kode.

Begreber Forklaret
-------------------
* GitHub Actions:
Et værktøj til at automatisere softwareudviklingsprocesser direkte i dit GitHub repository.
Det giver dig mulighed for at definere workflows,
der køres ved bestemte begivenheder som for eksempel en kode-commit.

* Workflow:
En sekvens af jobs, der bliver kørt, når en bestemt begivenhed (f.eks. en commit) opstår.
Workflows defineres i YAML-filer, som placeres i .github/workflows mappen i dit projekt.

* Job:
Et job er en sektion i et workflow, der indeholder en række handlinger (actions), som køres sekventielt på en bestemt virtuel maskine.
Jobs kan konfigureres til at køre parallelt eller sekventielt.

* Action:
En individuel handling inden for et job.
Actions kan være prædefinerede opgaver som f.eks. at køre en shell-kommando, tjekke kode ud, eller installere afhængigheder.

* Event:
En begivenhed, der trigger et workflow.
Et eksempel på en event kan være push, som aktiverer workflowet, når ny kode bliver skubbet til repositoryen.

* YAML:
Et menneskeligt læsbart dataformat, der bruges til at konfigurere workflows i GitHub Actions.
YAML-filer er hierarkiske og består af nøgleværdipar, lister og objekter.

Ved at forstå og bruge disse begreber kan du effektivt automatisere dine udviklingsprocesser, hvilket sparer tid og reducerer risikoen for fejl.
