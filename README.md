*{

    margin: 0;

    padding: 0;

    box-sizing: border-box;

    font-family: 'poppins',sans-serif;

}

section

{

    position: relative;

    width: 100%;

    min-height: 100vh;

    padding: 100px;

    display: flex;

    justify-content: space-between;

    align-items: center;

    background-color: #0062be;

    transition: 0.5s;

}   

header

{

    position: absolute;

    top: 0;

    left: 0;

    width: 100%;

    padding: 20px 100px;

    display: flex;

    justify-content: space-between;

    align-items: center;

}

header .logo

{

    position: relative;

    max-width: 80px;

}

header ul

{

    position: relative;

    display: flex;

}

header ul li

{

    list-style: none;

}

header ul li a

{

    display: inline-block;

    color: #fff;

    font-weight: 400;

    margin-left: 40px;

    text-decoration: none;

}

.content

{

    position: relative;

    width:100%;

    display: flex;

    justify-content: space-between;

    align-items: center;

}  

.content .textBox

{

    position: relative;

    max-width: 600px;

}   

.content .textBox h2

{

    color:#fff;

    font-size: 4em;

    line-height: 1.5em;

    text-transform: uppercase;

}

.content .textBox h2 span

{

   font-size: 2em; 

}

.content .textBox p

{

    color: #fff;

}

.content .textBox a

{

    display: inline-block;

    margin-top: 20px;

    padding: 8px 20px;

    background: #fff;

    color: #111;

    border-radius: 40px;

    letter-spacing: 1px;

    text-decoration: none;

    text-transform: uppercase;

}

.content .imgBox

{

    width: 600px;

    display: flex;

    padding-right: 50px;

    margin-top: 50px;

    justify-content: flex-end;

}

.content .imgBox

{

    max-width: 260px;

}

.thumb

{

    position: absolute;

    left: 50%;

    bottom: 20px;

    transform: translateX(-50%);

    display: flex;

}

.thumb li

{

    list-style: none;

    display: inline-block;

    margin: 0 20px;

    cursor: pointer;

    transition: 0.5s;

}

.thumb li:hover

{

    transform: translateY(-15px);

}

.thumb li img

{

    max-width: 40px;

}

.sci

{

    position: absolute;

    top: 50%;

    right: 30px;

    transform: translateY(-50%);

    display: flex;

    justify-content: center;

    align-items: center;

    flex-direction: column;

}

.sci li

{

    list-style: none;

}

.sci li a

{ 

    display: inline-block;

    filter: invert(1);

    margin: 5px 0;

    transform: scale(0.6);

}
