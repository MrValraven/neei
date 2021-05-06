<template>
    <footer>
		<ul class="ulContainer">
            <div class="neei">
                <h1>Logotipo do NEEI<br> em branco</h1>
                <p>O NEEI tem como objectivo apoiar os alunos do departamento de informática da Universidade de Évora, tanto a nivel escolar, como a nivel professional.</p> 
            </div>
            <div class="contactInfo">
                <h1>Contactos</h1>
                <li>
                    <a href="https://www.google.com/maps/place/Col%C3%A9gio+Lu%C3%ADs+Ant%C3%B3nio+Verney/@38.5684011,-7.9102123,19.73z/data=!4m9!1m2!2m1!1sRom%C3%A3o+Ramalho,+n%C2%BA59+7000-671+%C3%89vora,+Portugal!3m5!1s0x0:0x2be037428d567c55!8m2!3d38.5685418!4d-7.910526!15sCi9Sb23Do28gUmFtYWxobywgbsK6NTkgNzAwMC02NzEgw4l2b3JhLCBQb3J0dWdhbJIBCnVuaXZlcnNpdHk" target="_blank" rel="noopenner">
                    <i class="fas fa-map-marker-alt icon" aria-hidden="true"></i>
                    <p>Romão Ramalho, nº59 <br>7000-671 Évora, Portugal</p>
                    </a>
                    
                </li>
                <li>
                    <a href="mailto:geral@aaue.pt">
                        <i class="fas fa-envelope icon" aria-hidden="true"></i>
                        <p>iogeral@neei.uevora.pt</p>
                    </a>
                </li>
            </div>
            <div class="socials">
                <h1>Redes Sociais</h1>
                <div class="icons">
                    <li>
                        <a class="icon" id="facebook" href="hhttps://www.facebook.com/neeiue" target="_blank">
                            <i class="fab fa-facebook-square"></i>
                             <p>@neeiue</p> 
                        </a>
                    </li>
                    <li>
                        <a class="icon" id="instagram" href="https://www.instagram.com/neeiue/" target="_blank">
                            <i class="fab fa-instagram"></i>
                             <p>@neeiue</p> 
                        </a>
                    </li>
			        <li>
                        <a class="icon" id="linkedin" href="https://www.linkedin.com/company/neei-ue/" target="_blank">
                            <i class="fab fa-linkedin-in"></i>
                            <p>NEEI-UE</p> 
                        </a>
                    </li>  
			        <li>
                        <a class="icon" id="github" href="https://github.com/NEEI-UEvora" target="_blank">
                            <i class="fab fa-github-square"></i>
                            <p>NEEI-UEvora</p> 
                        </a>
                    </li>  
                </div>
            </div>
		</ul>
		
	</footer>
</template>

<script >

export default {
  name: 'Footer',
};
</script>

<style lang="scss" scoped>
$textColor: #f7f7f7;
$backgroundColor: #171717;

footer {
	display: flex;
	flex-direction: column;
    justify-content: space-around;
	color: $textColor;
	background-color: $backgroundColor;
	padding-top: 30px;

    .ulContainer {
        display: flex;
        margin-bottom: 25px;
        font-size: 32px;
        justify-content: space-around;
        .neei {
            display: flex;
            flex-direction: column;
            width: 20%;
            height: 100%;

            h1 {
                color: $textColor;
                opacity: 0.9;
                font-size: 30px;
                margin-bottom: 30px;
            }
        }
        .contactInfo {
            display: flex;
            flex-direction: column;
            justify-content: center;
            height: 100%;
            h1 {
                color: $textColor;
                opacity: 0.9;
                font-size: 30px;
            }
            li {
                display: flex;
                flex-direction: row;
                align-items: center;
                height: 35px;
                padding-top: 40px;
                margin: 10px 8px;
                a {
                    display: flex;
                    align-items: center;
                    color: $textColor;
                    margin-right: 10px;
                    i {
                        margin-right: 10px;
                    }
                }
                .icon {
                    display: flex;
                    justify-content: center;
                   
                }
                .fa-phone {
                    color:#89CFF0;
                }
                .fa-map-marker-alt {
                    color:#e96656;
                }
                .fa-envelope {
                    color:#90EE90;
                }
                .fa-fax {
                    color:#ffc0cb;
                }
                &:first-child{
                    margin-left: 0;	
                }
                &:last-child{
                    margin-right: 0;	
                }
            }
        }
    }
   
    .socials {
        display: flex;
        flex-direction: column;
        justify-content: center;
        height: 100%;

         h1 {
            color: $textColor;
            opacity: 0.9;
            font-size: 30px;
        }

        .icons {
            display: flex;
            flex-direction: column;
            justify-content: center;
            color: $textColor;
            .icon {
                display: flex;
                align-items: center;
                text-align: center;
                color: $textColor;
                font-size: 20px;
                margin: 5px 0 5px 0;
                i {
                    margin: 10px 10px 0 0;
                    font-size: 30px;
                }
                p {
                    text-transform: uppercase;
                    color: $textColor;
                    margin: 10px 0 0 0;
                    transition: color 0.2s ease-in;
                }
            }
            #instagram:hover,
             #instagram:hover p {
                color: #8a3ab9;
            }
            #github:hover,
             #github:hover p {
                color: #8a3ab9;
            }
            #facebook:hover,
            #facebook:hover p {
                color: #3b5998;
            }
            #linkedin:hover,
            #linkedin:hover p {
                color: #2867B2;
            }
        }
    }
    p{
        font-size: 16px;
    }
}
@media (max-width: 700px){
	footer {
		padding: 80px 15px;
	}
}
</style>