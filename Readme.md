
# Simple Api Using NodeJS

## **About:**

This project was developed using Express and NodeJs serving as a basis for creating APIs with these technologies.

## **Tools:**

This project used NodeJS on base and Express to generate the comunication.

## **Installation:**
Download or clone the repository. Then:

**yarn install or npm install**
## **Usage:**

- **GET**: <you_url>/repositories

    This method returns all registered repositories

- **POST** : <you_url>/repositories

    Creates a new repositorie with this attributes:

    - id:  self created.
    - title: string → mandatory.
    - url: string → mandatory.
    - techs: string → mandatory.
    - likes: number → starts on 0.

- **PUT**: <you_url>/repositories/<id>

    Changes the repository data according to the passed id

- **DELETE**: <you_url>/repositories/<id>

     Delete the repository data according to the passed id

- **POST**:<you_url>/repositories/<id>/likes

    Pass the repository id and add a like to it
