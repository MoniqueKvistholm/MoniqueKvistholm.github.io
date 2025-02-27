---
layout: page2
permalink: /team/
title: Team
nav: true
nav_order: 3
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Team Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        .team-container {
            text-align: left;
            padding: 0px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .organization-container {
            text-align: left;
            background-color: #EBF8FF;
            padding-top: 50px; /* Kun top-padding */
            margin: 0; /* Fjern automatisk margin */
            width: 100%; /* Sørg for at boksen fylder hele bredden */
            box-sizing: border-box; /* Sørg for at padding og border inkluderes i elementets totale bredde */
        }

        .intro-section {
            background-color: #6A5B4E; 
            padding: 60px; /* Tilføj lidt padding */
            text-align: left; /* Center tekst og billede */
            width: 100%; /* Fuld bredde */
            box-sizing: border-box; /* Inkluder padding i bredden */
        }

        .team-intro {
            margin: 0 150px; /* Juster marginen som ønsket */
            font-size: 30px; /* Juster skriftstørrelsen */
            line-height: 1.9; /* Øg linjehøjden for bedre læsbarhed */
            text-align: center; /* Center tekst og billede */
            /*font-weight: bold; */
        }


        .team-section {
            background-color: #E6DED0; 
            padding: 15px; /* Tilføj lidt padding */
            text-align: left; /* Center tekst og billede */
            width: 100%; /* Fuld bredde */
            box-sizing: border-box; /* Inkluder padding i bredden */
        }

        .team-title {
        color: #062a40; /* Mørkeblå farve */
        }


        .tab-container {
            display: flex;
            justify-content: center;
            margin-bottom: 20px;
            border-bottom: 2px solid #ccc;
            position: relative;
        }

        .tab-button {
            background-color: transparent;
            border: none;
            padding: 10px 10px;
            cursor: pointer;
            font-size: 25px;
            font-weight: normal;
            color: #666;
            transition: color 0.3s;
            position: relative;
            text-align: center;
            flex: 1;
        }

        .tab-button.active {
            font-weight: bold;
            color: #000;
        }

        .tab-button.active::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: -1px;
            width: 100%;
            height: 2px;
            background-color: #001a33;
            border-radius: 1px;
        }

        .tab-button:hover {
            color: #333;
        }

        .tab-content {
            display: none;
            padding: 20px;
        }

        .team-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
            gap: 20px;
            padding: 0;
        }

        .team-member {
            text-align: left;
            cursor: pointer;
            transition: none;
        }

        .team-member img {
            width: 100%;
            height: auto;
            object-fit: cover;
            border: none;
            margin-bottom: 10px;
            display: block;
        }

        .team-member h3 {
            margin: 10px 0 5px;
            font-weight: bold;
            font-size: 24px;
        }

        .team-member p {
            color: #666;
            margin: 0;
            font-size: 20px;
        }

        .modal {
            display: none;
            position: fixed;
            z-index: 1;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            overflow: auto;
            background-color: rgba(0, 0, 0, 0.6);
            backdrop-filter: blur(5px);
        }

        .modal-content {
            background-color: #fff;
            margin: 5% auto;
            padding: 20px;
            width: 60%;
            max-width: 600px;
            text-align: left;
            position: relative;
            border-radius: 0;
        }

        .modal img {
            width: 100%;
            height: auto;
            object-fit: cover;
            border: none;
            margin-bottom: 20px;
        }

        .modal-content strong {
            font-weight: bold;
}


        .close {
            color: #aaa;
            font-size: 28px;
            font-weight: bold;
            position: absolute;
            top: 10px;
            right: 20px;
        }

        .close:hover,
        .close:focus {
            color: black;
            text-decoration: none;
            cursor: pointer;
        }

        .modal h3 {
            margin: 10px 0 5px;
            font-weight: bold;
            font-size: 24px;
        }

        .modal p {
            color: #666;
            margin: 0;
        }

        .modal .additional-details {
            color: #000 !important;
            margin-top: 15px;
        }
        
        /* Styling for links */
        a {
            color:rgb(90, 163, 246); /* Blå farve */
            text-decoration: none; /* Fjern understregning */
        }

        a:hover {
            text-decoration: underline; /* Understregning ved hover */
        }

        /* Styling for links inde i modals */
        .modal a {
            color: rgb(90, 163, 246); /* Blå farve */
        }

        .modal a:hover {
            text-decoration: underline; /* Understregning ved hover */
        }

        /* Styling for Organization sektion */
        .organization-section {
            background-color: #EBF8FF; /* Lys blå baggrundsfarve */
            padding: 50px; /* Tilføj lidt padding */
            text-align: left; /* Center tekst og billede */
            width: 100%; /* Fuld bredde */
            box-sizing: border-box; /* Inkluder padding i bredden */
        }

        .organization-section img {
            max-width: 100%; /* Sørg for, at billedet ikke overskrider containerens bredde */
            height: auto; /* Bevar billedets aspektforhold */
            border: none; /* Ingen kantlinje */
        }

        /* Container inden i Organization sektionen for at centrere indhold */
        .organization-section .container {
            max-width: 1250px; /* Max bredde for indholdet */
            margin: 0 auto; /* Center containeren */
            padding: 0 30px; /* Padding på siderne */
        }

        /* For store skærme, fx desktop */
        .team-grid {
            grid-template-columns: repeat(4, 1fr); /* 4 kolonner på store skærme */
            gap: 30px;
        }

        /* For mellemstore skærme, fx tablets og mindre desktops */
        @media only screen and (max-width: 1200px) {
            .team-grid {
                grid-template-columns: repeat(3, 1fr); /* 3 kolonner på mellemstore skærme */
                gap: 25px;
            }

            .team-member {
                transform: scale(0.95); /* Let skaleret */
            }
        }

        /* For mindre tablets og store mobilskærme */
        @media only screen and (max-width: 992px) {
            .team-grid {
                grid-template-columns: repeat(2, 1fr); /* 2 kolonner på mindre tablets */
                gap: 20px;
            }

            .team-member {
                transform: scale(0.9); /* Skalerer en smule ned */
            }
        }

        /* Dette er media queries for små skærme (mobil) */
        @media only screen and (max-width: 768px) {
            .team-grid {
                grid-template-columns: 1fr; /* 1 kolonne på helt små skærme */
                gap: 15px;
            }

            .team-member {
                transform: scale(0.85); /* Skalerer boksene lidt ned */
            }

            /* Her er de andre ændringer for små skærme */
            .team-container, .organization-container, .intro-section, .team-section {
                padding: 10px;
                margin: 0;
            }

            .team-intro {
                margin: 0 15px;
                font-size: 20px;
            }

            .team-title {
                font-size: 24px;
            }

            .tab-button {
                font-size: 16px; /* Mindre skriftstørrelse til tabs */
                padding: 8px;
            }

            .modal-content {
                width: 90%; /* Mindre modal bredde */
                margin: 10% auto;
                padding: 15px;
            }

            .organization-section {
                padding: 30px 10px;
            }

            .organization-section .container {
                padding: 0;
            }

            .team-member h3 {
                font-size: 18px;
            }

            .team-member p {
                font-size: 16px;
            }

            .team-intro p {
                font-size: 18px; /* Tilpas skriftstørrelsen på intro-teksten */
            }
        }

    </style>
</head>
<body>
    <div class="intro-section">
    <div style="height: 0px;"></div>
    <!-- Intro-sektion -->
    <div class="team-intro">
        <p style="color: #f2e6d9;">Welcome to our interdisciplinary team! Here, you can meet the members of DEPICT. Our strength lies in the diverse expertise of our members, who drive our projects to optimize imaging techniques and enhance diagnostic capabilities.</p>
    </div>
    <div style="height: 0px;"></div>
</div>


    <div class="team-section">
    <div class="team-container">
        <div style="height: 50px;"></div>
        <h1 class="team-title">Team</h1>
        <div style="height: 65px;"></div>
        <div class="tab-container">
            <button class="tab-button" onclick="showTab('center-managers')">Center Managers</button>
            <button class="tab-button" onclick="showTab('steering-committee')">Steering Committee</button>
            <button class="tab-button" onclick="showTab('ai-research-directors')">AI Research Directors</button>
            <button class="tab-button" onclick="showTab('board-of-directors')">Board of Directors</button>
            <button class="tab-button" onclick="showTab('associated-researchers')">Associated Researchers</button>
            <button class="tab-button" onclick="showTab('phd-students')">PhD Students</button>
        </div>

        <div style="height: 10px;"></div>

        <!-- Center Managers -->
        <div id="center-managers" class="tab-content">
            <div class="team-grid">
                <div class="team-member" onclick="openModal('modal1')">
                    <img src="/assets/img/Flemming_person.png" alt="Flemming Littrup Andersen">
                    <h3>Flemming Littrup Andersen</h3>
                    <p>Lead Data Scientist </p>
                </div>
                <div class="team-member" onclick="openModal('modal2')">
                    <img src="/assets/img/Adam_person.png" alt="Adam Espe Hansen">
                    <h3>Adam Espe Hansen</h3>
                    <p>Professor</p>
                </div>
            </div>
        </div>

        <!-- Steering Committee -->
        <div id="steering-committee" class="tab-content" style="display:none;">
            <div class="team-grid">
                <div class="team-member" onclick="openModal('modal3')">
                    <img src="/assets/img/Jann_person.png" alt="Jann Mortensen">
                    <h3>Jann Mortensen</h3>
                    <p>Professor, Chief Physician</p>
                </div>
                <div class="team-member" onclick="openModal('modal4')">
                    <img src="/assets/img/Flemming_person.png" alt="Flemming Littrup Andersen">
                    <h3>Flemming Littrup Andersen</h3>
                    <p>Lead Data Scientist</p>
                </div>
                <div class="team-member" onclick="openModal('modal5')">
                    <img src="/assets/img/Claes_person.png" alt="Claes Ladefoged">
                    <h3>Claes Ladefoged</h3>
                    <p>Associate Professor</p>
                </div>
                <div class="team-member" onclick="openModal('modal6')">
                    <img src="/assets/img/Adam_person.png" alt="Adam Espe Hansen">
                    <h3>Adam Espe Hansen</h3>
                    <p>Professor</p>
                </div>
                <div class="team-member" onclick="openModal('modal7')">
                    <img src="/assets/img/Michael_person.png" alt="Michael Bachmann">
                    <h3>Michael Bachmann</h3>
                    <p>Professor, Chief Physician</p>
                </div>
                <div class="team-member" onclick="openModal('modal8')">
                    <img src="/assets/img/Jonathan_person.png" alt="Jonathan Carlsen">
                    <h3>Jonathan Carlsen</h3>
                    <p>Chief Physician</p>
                </div>
                <div class="team-member" onclick="openModal('modal9')">
                    <img src="/assets/img/Martin_person.png" alt="Martin Lundsgaard">
                    <h3>Martin Lundsgaard</h3>
                    <p>Chief Physician</p>
                </div>
                <div class="team-member" onclick="openModal('modal10')">
                    <img src="/assets/img/Ian_person.png" alt="Ian Law">
                    <h3>Ian Law</h3>
                    <p>Professor, Chief Physician</p>
                </div>
                <div class="team-member" onclick="openModal('modal11')">
                    <img src="/assets/img/Ida_person.png" alt="Ida Robsøe">
                    <h3>Ida Robsøe</h3>
                    <p>Chief Bioanalyst</p>
                </div>
                <div class="team-member" onclick="openModal('modal12')">
                    <img src="/assets/img/Johnny_person.png" alt="Johnny Madelung">
                    <h3>Johnny Madelung</h3>
                    <p>Lead Radiographer</p>
                </div>
                <div class="team-member" onclick="openModal('modal24')">
                    <img src="/assets/img/placeholder_person.png" alt="Ulrik Lindberg">
                    <h3>Ulrik Lindberg</h3>
                    <p>MR physicist</p>
                </div>
                <div class="team-member" onclick="openModal('modal26')">
                    <img src="/assets/img/ThomasH_person.png" alt="Thomas Hartvig">
                    <h3>Thomas Hartvig</h3>
                    <p>Senior Hospital Physician</p>
                </div>
            </div>
        </div>

        <!-- AI Research Directors -->
        <div id="ai-research-directors" class="tab-content" style="display:none;">
            <div class="team-grid">
                <div class="team-member" onclick="openModal('modal13')">
                    <img src="/assets/img/Claes_person.png" alt="Claes Ladefoged">
                    <h3>Claes Ladefoged</h3>
                    <p>Associate Professor</p>
                </div>
                <div class="team-member" onclick="openModal('modal14')">
                    <img src="/assets/img/Michael_person.png" alt="Michael Bachmann">
                    <h3>Michael Bachmann</h3>
                    <p>Professor, Chief Physician</p>
                </div>
            </div>
        </div>

        <!-- Board of Directors -->
        <div id="board-of-directors" class="tab-content" style="display:none;">
            <div class="team-grid">
                <div class="team-member" onclick="openModal('modal15')">
                    <img src="/assets/img/Randi_person.png" alt="Randi Brinckmann">
                    <h3>Randi Brinckmann</h3>
                    <p>Center Director</p>
                </div>
                <div class="team-member" onclick="openModal('modal16')">
                    <img src="/assets/img/Martin_person.png" alt="Martin Lundsgaard">
                    <h3>Martin Lundsgaard</h3>
                    <p>Chief Physician</p>
                </div>
                <div class="team-member" onclick="openModal('modal17')">
                    <img src="/assets/img/Jann_person.png" alt="Jann Mortensen">
                    <h3>Jann Mortensen</h3>
                    <p>Professor, Chief Physician</p>
                </div>
            </div>
        </div>

        <!-- Ph.D Students -->
        <div id="phd-students" class="tab-content" style="display:none;">
            <div class="team-grid">
                <div class="team-member" onclick="openModal('modal18')">
                    <img src="/assets/img/Christian_person.png" alt="Christian Hinge">
                    <h3>Christian Hinge</h3>
                    <p>PhD Student</p>
                </div>
                <div class="team-member" onclick="openModal('modal19')">
                    <img src="/assets/img/placeholder_person.png" alt="Amalie Monberg Hindsholm">
                    <h3>Amalie Monberg Hindsholm</h3>
                    <p>PhD Student</p>
                </div>
                <div class="team-member" onclick="openModal('modal20')">
                    <img src="/assets/img/Nanna_person.png" alt="Nanna Overbeck Petersen">
                    <h3>Nanna Overbeck Petersen</h3>
                    <p>PhD Student</p>
                </div>
                <div class="team-member" onclick="openModal('modal21')">
                    <img src="/assets/img/placeholder_person.png" alt="David Kovacs Petersen">
                    <h3>David Kovacs Petersen</h3>
                    <p>PhD Student</p>
                </div>
                <div class="team-member" onclick="openModal('modal23')">
                    <img src="/assets/img/Peter_person.png" alt="Peter Jagd Sørensen">
                    <h3>Peter Jagd Sørensen</h3>
                    <p>PhD Student</p>
                </div>
                <div class="team-member" onclick="openModal('modal25')">
                    <img src="/assets/img/placeholder_person.png" alt="Lea Marie Pehrson">
                    <h3>Lea Marie Pehrson</h3>
                    <p>PhD Student</p>
                </div>
            </div>
        </div>

        <!-- Associated Researchers -->
        <div id="associated-researchers" class="tab-content" style="display:none;">
            <div class="team-grid">
                <div class="team-member" onclick="openModal('modal22')">
                    <img src="/assets/img/placeholder_person.png" alt="Thomas Lund Andersen">
                    <h3>Thomas Lund Andersen</h3>
                    <p>Physicist</p>
                </div>
            </div>
        </div>

        <!-- Placeholder for footer positioning -->
        <div style="height: 200px;"></div>
    </div>
    </div>

    <!-- Modals -->
    <div id="modal1" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal1')">&times;</span>
            <img src="/assets/img/Flemming_person.png" alt="Flemming Littrup Andersen">
            <h3>Flemming Littrup Andersen</h3>
            <p>Datachef</p>
            <div style="height: 15px;"></div>
            <div style="white-space: nowrap;"> <strong>Publications:</strong> <a href="https://research.regionh.dk/en/persons/flemming-littrup-andersen/publications/" target="_blank">Click to view Flemming's publications</a> </div>

            <p class="additional-details">
                Flemming Littrup Andersen is a Lead Data Scientist at Rigshospitalet, specializing in PET imaging, artificial intelligence, dataflow, and image modeling. He holds a PhD and brings extensive expertise to his role in advancing these fields.
                <br><br>
                Email: <a href="mailto:flemming.andersen@regionh.dk">flemming.andersen@regionh.dk</a>
                <br>
                Phone: <a href="tel:+4535458143">+45 35-45 81-43</a>
                <br>
                Location: 3982, Clinical Physiology and Nuclear Medicine
            </p>
        </div>
    </div>

    <div id="modal2" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal2')">&times;</span>
            <img src="/assets/img/Adam_person.png" alt="Adam Espe Hansen">
            <h3>Adam Espe Hansen</h3>
            <p>Professor</p>
            <div style="height: 15px;"></div>
            <div style="white-space: nowrap;"> <strong>Publications:</strong> <a href="https://research.regionh.dk/en/persons/adam-espe-hansen/publications/" target="_blank">Click to view Adam's publications</a> </div>
            <p class="additional-details">
                Adam Espe Hansen is a Clinical Professor of Radiology with a special focus on Magnetic Resonance Imaging (MRI) Physics.
                <br><br>
                Email: <a href="mailto:adam.espe.hansen@regionh.dk">adam.espe.hansen@regionh.dk</a>
                <br>
                Phone: <a href="tel:+4535458460">+45 35-45 84-60</a>
                <br>
                Location: 3023, Radiology
            </p>
        </div>
    </div>


    <div id="modal3" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal3')">&times;</span>
            <img src="/assets/img/Jann_person.png" alt="Jann Mortensen">
            <h3>Jann Mortensen</h3>
            <p>Professor, Chief Physician, Dr. Med</p>
            <div style="height: 15px;"></div>
            <div style="white-space: nowrap;"> <strong>Publications:</strong> <a href="https://research.regionh.dk/en/persons/jann-mortensen/publications/" target="_blank">Click to view Jann's publications</a> </div>
            <p class="additional-details">
                Email: <a href="mailto:jann.mortensen@regionh.dk">jann.mortensen@regionh.dk</a>
                <br>
                Phone: <a href="tel:+4535451716">+45 35-45 17-16</a>
                <br>
                Location: 4011, Clinical Physiology and Nuclear Medicines
            </p>
        </div>
    </div>


    <div id="modal4" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal4')">&times;</span>
            <img src="/assets/img/Flemming_person.png" alt="Flemming Littrup Andersen">
            <h3>Flemming Littrup Andersen</h3>
            <p>Datachef</p>
            <div style="height: 15px;"></div>
            <div style="white-space: nowrap;"> <strong>Publications:</strong> <a href="https://research.regionh.dk/en/persons/flemming-littrup-andersen/publications/" target="_blank">Click to view Flemming's publications</a> </div>

            <p class="additional-details">
                Flemming Littrup Andersen is a Lead Data Scientist at Rigshospitalet, specializing in PET imaging, artificial intelligence, dataflow, and image modeling. He holds a PhD and brings extensive expertise to his role in advancing these fields.
                <br><br>
                Email: <a href="mailto:flemming.andersen@regionh.dk">flemming.andersen@regionh.dk</a>
                <br>
                Phone: <a href="tel:+4535458143">+45 35-45 81-43</a>
                <br>
                Location: 3982, Clinical Physiology and Nuclear Medicine
            </p>
        </div>
    </div>

    <div id="modal5" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal5')">&times;</span>
            <img src="/assets/img/Claes_person.png" alt="Claes Ladefoged">
            <h3>Claes Ladefoged</h3>
            <p>Associate Professor</p>
            <div style="height: 15px;"></div>
            <div style="white-space: nowrap;"> <strong>Publications:</strong> <a href="https://research.regionh.dk/en/persons/claes-n%C3%B8hr-ladefoged/publications/" target="_blank">Click to view Claes's publications</a> </div>
            <p class="additional-details">
                Email: <a href="mailto:claes.noehr.ladefoged@regionh.dk">claes.noehr.ladefoged@regionh.dk</a>
                <br>
                Phone: <a href="tel:+4535454790">+45 35-45 47-90</a>
                <br>
                Location: 3982, Clinical Physiology and Nuclear Medicine
            </p>
        </div>
    </div>

    <div id="modal6" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal6')">&times;</span>
            <img src="/assets/img/Adam_person.png" alt="Adam Espe Hansen">
            <h3>Adam Espe Hansen</h3>
            <p>Professor</p>
            <div style="height: 15px;"></div>
            <div style="white-space: nowrap;"> <strong>Publications:</strong> <a href="https://research.regionh.dk/en/persons/adam-espe-hansen/publications/" target="_blank">Click to view Adam's publications</a> </div>
            <p class="additional-details">
                Adam Espe Hansen is a Clinical Professor of Radiology with a special focus on Magnetic Resonance Imaging (MRI) Physics.
                <br><br>
                Email: <a href="mailto:adam.espe.hansen@regionh.dk">adam.espe.hansen@regionh.dk</a>
                <br>
                Phone: <a href="tel:+4535458460">+45 35-45 84-60</a>
                <br>
                Location: 3023, Radiology
            </p>
        </div>
    </div>

    <div id="modal7" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal7')">&times;</span>
            <img src="/assets/img/Michael_person.png" alt="Michael Bachmann">
            <h3>Michael Bachmann</h3>
            <p>Professor, Chief Physician</p>
            <div style="height: 15px;"></div>
            <div style="white-space: nowrap;"> <strong>Publications:</strong> <a href="https://research.regionh.dk/en/persons/michael-bachmann-nielsen/publications/" target="_blank">Click to view Michael's publications</a> </div>
            <p class="additional-details">
                Email: <a href="mailto:mbn@dadlnet.dk">mbn@dadlnet.dk</a>
                <br>
                Phone: <a href="tel:+4535453419">+45 35-45 34-19</a>
                <br>
                Location: 3023, Radiology
            </p>
        </div>
    </div>

    <div id="modal8" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal8')">&times;</span>
            <img src="/assets/img/Jonathan_person.png" alt="Jonathan Carlsen">
            <h3>Jonathan Carlsen</h3>
            <p>Chief Physician</p>
            <div style="height: 15px;"></div>
            <div style="white-space: nowrap;"> <strong>Publications:</strong> <a href="https://research.regionh.dk/en/persons/jonathan-frederik-carlsen/publications/" target="_blank">Click to view Jonathan's publications</a> </div>
            <p class="additional-details">
                Email: <a href="mailto:jonathan.frederik.carlsen@regionh.dk">jonathan.frederik.carlsen@regionh.dk</a>
                <br>
                Location: 2023, Radiology
            </p>
        </div>
    </div>

    <div id="modal9" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal9')">&times;</span>
            <img src="/assets/img/Martin_person.png" alt="Martin Lundsgaard">
            <h3>Martin Lundsgaard</h3>
            <p>Chief Physician</p>
            <p class="additional-details">
                Email: <a href="mailto:martin.lundsgaard.hansen@regionh.dk">martin.lundsgaard.hansen@regionh.dk</a>
                <br>
                Phone: <a href="tel:+4521600236">+45 21-60 02-36</a>
                <br>
                Location: 2023, Radiology
            </p>
        </div>
    </div>

    <div id="modal10" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal10')">&times;</span>
            <img src="/assets/img/Ian_person.png" alt="Ian Law">
            <h3>Ian Law</h3>
            <p>Professor, Chief Physician </p>
            <div style="height: 15px;"></div>
            <div style="white-space: nowrap;"> <strong>Publications:</strong> <a href="https://research.regionh.dk/en/persons/ian-law/publications/" target="_blank">Click to view Ian's publications</a> </div>
            <p class="additional-details">
                Email: <a href="mailto:ian.law@regionh.dk">ian.law@regionh.dk</a>
                <br>
                Phone: <a href="tel:+4530295122">+45 30-29 51-22 </a>
                <br>
                Location: 3982, Radiology
            </p>
        </div>
    </div>

    <div id="modal11" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal11')">&times;</span>
            <img src="/assets/img/Ida_person.png" alt="Ida Robsøe">
            <h3>Ida Robsøe</h3>
            <p>Chief Bioanalyst</p>
            <p class="additional-details">
                Email: <a href="mailto:ida.robsoee@regionh.dk">ida.robsoee@regionh.dk</a>
                <br>
                Phone: <a href="tel:+4535459503">+45 35-45 95-03 </a>
                <br>
                Location: 4011, Radiology
            </p>
        </div>
    </div>

    <div id="modal12" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal12')">&times;</span>
            <img src="/assets/img/Johnny_person.png" alt="Johnny Madelung">
            <h3>Johnny Madelung</h3>
            <p>Lead Radiographer</p>
            <p class="additional-details">
                Email: <a href="mailto:johnny.madelung@regionh.dk">johnny.madelung@regionh.dk</a>
                <br>
                Phone: <a href="tel:+4535451666">+45 35-45 16-66 </a>
                <br>
                Location: 2023, Radiology
            </p>
        </div>
    </div>

    <div id="modal13" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal13')">&times;</span>
            <img src="/assets/img/Claes_person.png" alt="Claes Ladefoged">
            <h3>Claes Ladefoged</h3>
            <p>Postdoc</p>
            <div style="height: 15px;"></div>
            <div style="white-space: nowrap;"> <strong>Publications:</strong> <a href="https://research.regionh.dk/en/persons/claes-n%C3%B8hr-ladefoged/publications/" target="_blank">Click to view Claes's publications</a> </div>
            <p class="additional-details">
                Email: <a href="mailto:claes.noehr.ladefoged@regionh.dk">claes.noehr.ladefoged@regionh.dk</a>
                <br>
                Phone: <a href="tel:+4535454790">+45 35-45 47-90</a>
                <br>
                Location: 3982, Clinical Physiology and Nuclear Medicine
            </p>
        </div>
    </div>

    <div id="modal14" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal14')">&times;</span>
            <img src="/assets/img/Michael_person.png" alt="Michael Bachmann">
            <h3>Michael Bachmann Nielsen</h3>
            <p>Professor, Chief Physician</p>
            <div style="height: 15px;"></div>
            <div style="white-space: nowrap;"> <strong>Publications:</strong> <a href="https://research.regionh.dk/en/persons/michael-bachmann-nielsen/publications/" target="_blank">Click to view Michael's publications</a> </div>
            <p class="additional-details">
                Email: <a href="mailto:mbn@dadlnet.dk">mbn@dadlnet.dk</a>
                <br>
                Phone: <a href="tel:+4535453419">+45 35-45 34-19</a>
                <br>
                Location: 3023, Radiology
            </p>
        </div>
    </div>

    <div id="modal15" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal15')">&times;</span>
            <img src="/assets/img/Randi_person.png" alt="Randi Brinckmann">
            <h3>Randi Brinckmann</h3>
            <p>Center Director</p>
            <p class="additional-details">
                Email: <a href="mailto:randi.brinckmann@regionh.dk">randi.brinckmann@regionh.dk</a>
                <br>
                Phone: <a href="tel:+4535453252">+45 35-45 32-52</a>
                <br>
                Location: 4412, Center Management
            </p>
        </div>
    </div>

    <div id="modal16" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal16')">&times;</span>
            <img src="/assets/img/Martin_person.png" alt="Martin Lundsgaard">
            <h3>Martin Lundsgaard</h3>
            <p>Chief Physician</p>
            <p class="additional-details">
                Email: <a href="mailto:martin.lundsgaard.hansen@regionh.dk">martin.lundsgaard.hansen@regionh.dk</a>
                <br>
                Phone: <a href="tel:+4521600236">+45 21-60 02-36</a>
                <br>
                Location: 2023, Radiology
            </p>
        </div>
    </div>

    <div id="modal17" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal17')">&times;</span>
            <img src="/assets/img/Jann_person.png" alt="Jann Mortensen">
            <h3>Jann Mortensen</h3>
            <p>Professor, Chief Physician, Dr. Med</p>
            <p class="additional-details">
                Email: <a href="mailto:jann.mortensen@regionh.dk">jann.mortensen@regionh.dk</a>
                <br>
                Phone: <a href="tel:+4535451716">+45 35-45 17-16</a>
                <br>
                Location: 4011, Clinical Physiology and Nuclear Medicines
            </p>
        </div>
    </div>

    <div id="modal18" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal18')">&times;</span>
            <img src="/assets/img/Christian_person.png" alt="Christian Hinge">
            <h3>Christian Hinge</h3>
            <p>PhD Student</p>
            <div style="height: 15px;"></div>
            <div style="white-space: nowrap;"> <strong>Publications:</strong> <a href="https://research.regionh.dk/en/persons/christian-hinge/publications/" target="_blank">Click to view Christian's publications</a> </div>
            <p class="additional-details">
                Email: <a href="mailto:christian.hinge@regionh.dk">christian.hinge@regionh.dk</a>
                <br>
                Phone: <a href="tel:+4535457151">+45 35 45 71 51</a>
            </p>
        </div>
    </div>

    <div id="modal19" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal19')">&times;</span>
            <img src="/assets/img/placeholder_person.png" alt="Amalie Monberg Hindsholm">
            <h3>Amalie Monberg Hindsholm</h3>
            <p>PhD Student</p>
            <div style="height: 15px;"></div>
            <div style="white-space: nowrap;"> <strong>Publications:</strong> <a href="https://research.regionh.dk/en/persons/amalie-monberg-hindsholm/publications/" target="_blank">Click to view Amalie's publications</a> </div>
            <p class="additional-details">
                Email: <a href="mailto:amalie.monberg.hindsholm@regionh.dk">amalie.monberg.hindsholm@regionh.dk</a>
                <br>
                Phone: <a href="tel:+4523416424">+45 23 41 64 24</a>
            </p>
        </div>
    </div>

    <div id="modal20" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal20')">&times;</span>
            <img src="/assets/img/Nanna_person.png" alt="Nanna Overbeck">
            <h3>Nanna Overbeck</h3>
            <p>PhD Student</p>
            <div style="height: 15px;"></div>
            <div style="white-space: nowrap;"> <strong>Publications:</strong> <a href="https://research.regionh.dk/en/persons/nanna-overbeck-petersen/publications/" target="_blank">Click to view Nanna's publications</a> </div>
            <p class="additional-details">
                Email: <a href="mailto:nanna.overbeck.petersen.01@regionh.dk">nanna.overbeck.petersen.01@regionh.dk</a>
                <br>
                Phone: <a href="tel:+4535455126">+45 35 45 51 26</a>
            </p>
        </div>
    </div>

    <div id="modal21" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal21')">&times;</span>
            <img src="/assets/img/placeholder_person.png" alt="David Kovacs Petersen">
            <h3>David Kovacs Petersen</h3>
            <p>PhD Student</p>
            <div style="height: 15px;"></div>
            <div style="white-space: nowrap;"> <strong>Publications:</strong> <a href="https://research.regionh.dk/en/persons/david-gergely-petersen-kovacs/publications/" target="_blank">Click to view David's publications</a> </div>
            <p class="additional-details">
                Email: <a href="mailto:david.gergely.kovacs.petersen@regionh.dk">david.gergely.kovacs.petersen@regionh.dk</a>
                <br>
                Phone: <a href="tel:+4530470433">+45 30 47 04 33</a>
            </p>
        </div>
    </div>

    <div id="modal22" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal22')">&times;</span>
            <img src="/assets/img/placeholder_person.png" alt="Thomas Lund Andersen">
            <h3>Thomas Lund Andersen</h3>
            <p>Physicist</p>
            <div style="height: 15px;"></div>
            <div style="white-space: nowrap;"> <strong>Publications:</strong> <a href="https://research.regionh.dk/en/persons/thomas-lund-andersen/publications/" target="_blank">Click to view Thomas's publications</a> </div>
            <p class="additional-details">
                Email: <a href="mailto:thomas.lund.andersen@regionh.dk">thomas.lund.andersen@regionh.dk</a>
                <br>
                Phone: <a href="tel:+4535455373">+45 35 45 53 73</a>
            </p>
        </div>
    </div>

    <div id="modal23" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal23')">&times;</span>
            <img src="/assets/img/Peter_person.png" alt="Peter Jagd Sørensen">
            <h3>Peter Jagd Sørensen</h3>
            <p>PhD Student</p>
            <div style="height: 15px;"></div>
            <div style="white-space: nowrap;"> <strong>Publications:</strong> <a href="https://research.regionh.dk/en/persons/peter-jagd-s%C3%B8rensen" target="_blank">Click to view Peter's publications</a> </div>
            <p class="additional-details">
                Email: <a href="mailto:peter.jagd.soerensen@regionh.dk">peter.jagd.soerensen@regionh.dk</a>
                <br>
                Phone: <a href="tel:+4535452299">+45 35 45 22 99</a>
            </p>
        </div>
    </div>

    <div id="modal24" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal24')">&times;</span>
            <img src="/assets/img/placeholder_person.png" alt="Ulrik Lindberg">
            <h3>Ulrik Lindberg</h3>
            <p>MR physicist</p>
            <p class="additional-details">
                Email: <a href="mailto:ulrich.lindberg@regionh.dk">ulrich.lindberg@regionh.dk</a>
                <br>
                Phone: <a href="tel:+4538632737">+45 38 63 27 37</a>
            </p>
        </div>
    </div>


    <div id="modal25" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal25')">&times;</span>
            <img src="/assets/img/placeholder_person.png" alt="Lea Marie Pehrson">
            <h3>Lea Marie Pehrson</h3>
            <p>PhD Student</p>
            <p class="additional-details">
                Email: <a href="mailto:lea.marie.pehrson@gmail.com">lea.marie.pehrson@gmail.com</a>
            </p>
        </div>
    </div>

    <div id="modal26" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal26')">&times;</span>
            <img src="/assets/img/ThomasH_person.png" alt="Thomas Hartvig">
            <h3>Thomas Hartvig</h3>
            <p>Physicist</p>
            <div style="height: 15px;"></div>
            <div style="white-space: nowrap;"> <strong>Publications:</strong> <a href="https://research.regionh.dk/en/persons/thomas-hartvig-lindk%C3%A6r-jensen" target="_blank">Click to view Thomas's publications</a> </div>
            <p class="additional-details">
                Email: <a href="mailto:thomas.hartvig.lindkaer.jensen@regionh.dk">thomas.hartvig.lindkaer.jensen@regionh.dk</a>
                <br>
                Phone: <a href="tel:+4535455399">+45 35 45 53 99</a>
            </p>
        </div>
    </div>


    <script>
        function showTab(tabId) {
            var tabs = document.getElementsByClassName('tab-content');
            for (var i = 0; i < tabs.length; i++) {
                tabs[i].style.display = 'none';
            }

            var buttons = document.getElementsByClassName('tab-button');
            for (var i = 0; i < buttons.length; i++) {
                buttons[i].classList.remove('active');
            }

            document.getElementById(tabId).style.display = 'block';
            event.currentTarget.classList.add('active');
        }

        function openModal(modalId) {
            document.getElementById(modalId).style.display = "block";
        }

        function closeModal(modalId) {
            document.getElementById(modalId).style.display = "none";
        }

        // Viser den første tab som standard
        document.getElementsByClassName('tab-button')[0].click();
    </script>
</body>
</html>


