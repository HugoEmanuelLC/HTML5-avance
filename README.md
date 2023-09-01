## SEMANTIC HTML5

![Tux, the Linux mascot](./2ysa18v4r1mu3evmtiui.png)

![Tux, the Linux mascot](./1693472812759.png)

## Commentaires

- < !-- votre commentaire -- >

## Data Attributes

- data-nomAttribut="valeur"
- javascript ( 
    let test = document.getElementById('test').dataset.nomAttribut;
    console.log(test) //valeur
    )

[List d'atributs html ](https://developer.mozilla.org/es/docs/Web/HTML/Attributes)

## Forms

#### input

#### checkbox

    <label for="">checkbox1</label>
        <input type="checkbox" name="check" id="">
    <label for="">checkbox2</label>
        <input type="checkbox" name="check" id="">
    <label for="">checkbox3</label>
        <input type="checkbox" name="check" id="">

#### radio

    <label for="">Html5</label>
        <input type="radio" name="rad" id="" value="HTML">                    
    <label for="">Css3</label>
        <input type="radio" name="rad" id="" value="CSS">                    
    <label for="">JavaScript</label>
        <input type="radio" name="rad" id="" value="JavaScript">

#### select

    <select name="cars" id="cars">
        <option value="volvo">Volvo</option>
        <option value="saab">Saab</option>
        <option value="opel">Opel</option>
        <option value="audi">Audi</option>
    </select>