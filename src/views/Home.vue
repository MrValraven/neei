<template>
  <Navbar />
   <section class="hero">
      <div class="heroContent">
        <div class="textArea">
          <h1 class="slogan">Núcleo de Estudantes de<br>Engenharia Informática</h1>
          <p class="heroText">O NEEI tem como objectivo apoiar os alunos do departamento de informática da Universidade de Évora, tanto a nivel escolar, como a nivel professional.</p>
          <div class="buttons">
            <button class="vantagens">Junta-te à nossa comunidade!</button>
            <button v-if="socio" class="socio">Faz-te Sócio!</button>
          </div>
        </div>
        <img class="heroImage" src="@/assets/digitalNomad.svg" alt="">
      </div>
    </section>
    <section class="features">
      <h1>Como te podemos ajudar?</h1>
      <p class="subtitle">De modo a ajudar os alunos do curso, o NEEI organiza diversos eventos lúdicos e profissionais para aprimorar a vida académica dos estudantes</p>
      <div class="feature">
        <div class="palestra">
          <svg version="1.1" :width="width" :height="height" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
              viewBox="0 0 484.699 484.699" style="enable-background:new 0 0 484.699 484.699;" xml:space="preserve">
            <g id="XMLID_808_">
              <g id="XMLID_732_">
                <circle style="fill:#F7931E;" cx="333.231" cy="196.909" r="143.895"/>
              </g>
              <g id="XMLID_777_">
                <circle style="fill:#FBB03B;" cx="306.724" cy="200.696" r="117.388"/>
              </g>
              <g id="XMLID_810_">
                <polygon style="fill:#FFFFFF;" points="219.629,159.042 204.482,159.042 204.482,120.939 219.629,113.601 		"/>
              </g>
              <g id="XMLID_450_">
                <path style="fill:#E9483D;" d="M148.19,151.468h6.574c77.651,0,140.6,62.949,140.6,140.6v139.617H147.173
                  c-77.099,0-139.6-62.501-139.6-139.6l0,0C7.573,214.425,70.53,151.468,148.19,151.468z"/>
              </g>
              <g id="XMLID_645_">
                <circle style="fill:#ED6D64;" cx="128.748" cy="272.643" r="121.175"/>
              </g>
              <g id="XMLID_696_">
                <polygon style="fill:#FFFFFF;" points="30.293,355.951 13.008,336.24 13.008,231.439 30.293,219.629 		"/>
              </g>
              <g id="XMLID_449_">
                <g id="XMLID_430_">
                  <path style="fill:#1D1D1B;" d="M333.231,45.44c-62.799,0-118.579,38.439-141.149,96.419c-12.931-3.603-26.55-5.537-40.614-5.537
                    C67.948,136.322,0,204.27,0,287.79s67.948,151.469,151.468,151.469h151.469v-90.881h30.294
                    c83.52,0,151.468-67.948,151.468-151.468C484.699,113.389,416.751,45.44,333.231,45.44z M287.79,424.112H151.468
                    c-75.168,0-136.322-61.154-136.322-136.322S76.3,151.468,151.468,151.468S287.79,212.622,287.79,287.79V424.112z
                    M333.231,333.231h-30.294V287.79c0-64.121-40.052-119.059-96.45-141.123c20.488-51.787,70.477-86.081,126.744-86.081
                    c75.168,0,136.322,61.154,136.322,136.322C469.553,272.077,408.399,333.231,333.231,333.231z"/>
                  <g id="XMLID_428_">
                    <g id="XMLID_431_">
                      <path style="fill:#1D1D1B;" d="M110.513,265.044h15.324v8.272c0,3.617-0.429,6.305-1.287,8.069
                        c-0.862,1.764-2.737,4.094-5.628,6.986l-9.899,9.9c-2.082,2.259-3.121,5.063-3.121,8.405c0,3.347,1.087,6.128,3.254,8.343
                        c2.171,2.215,4.974,3.321,8.409,3.321s6.305-1.061,8.613-3.188c2.304-2.123,3.635-4.948,3.998-8.476h16.412
                        c-0.906,8.047-4.049,14.356-9.426,18.919c-5.381,4.567-12.092,6.849-20.139,6.849s-14.6-2.193-19.662-6.579
                        c-5.063-4.382-7.592-10.51-7.592-18.375c0-5.425,1.49-9.944,4.475-13.56c1.716-2.167,3.025-3.705,3.931-4.611
                        c0.902-0.902,2.104-2.052,3.594-3.458c1.49-1.398,2.755-2.618,3.798-3.661c1.035-1.039,1.875-1.964,2.507-2.781
                        c1.627-1.897,2.441-4.652,2.441-8.269v-6.106H110.513z M117.906,234.943c2.847,0,5.31,0.973,7.389,2.914
                        c2.078,1.945,3.121,4.293,3.121,7.052s-1.017,5.133-3.051,7.119c-2.034,1.99-4.478,2.984-7.326,2.984s-5.31-0.973-7.389-2.918
                        c-2.082-1.941-3.121-4.29-3.121-7.052c0-2.755,1.017-5.129,3.051-7.119C112.618,235.937,115.058,234.943,117.906,234.943z"/>
                    </g>
                    <g id="XMLID_441_">
                      <path style="fill:#1D1D1B;" d="M192.423,302.064h-15.324v-8.269c0-3.617,0.425-6.309,1.287-8.069
                        c0.858-1.764,2.733-4.09,5.628-6.986l9.899-9.9c2.078-2.259,3.117-5.063,3.117-8.405c0-3.347-1.084-6.124-3.254-8.343
                        c-2.171-2.211-4.974-3.321-8.405-3.321c-3.439,0-6.309,1.065-8.613,3.188s-3.639,4.948-4.001,8.476H156.35
                        c0.902-8.047,4.046-14.352,9.426-18.919c5.377-4.563,12.089-6.849,20.135-6.849c8.047,0,14.6,2.193,19.666,6.579
                        c5.059,4.386,7.592,10.51,7.592,18.375c0,5.421-1.49,9.944-4.475,13.56c-1.719,2.167-3.029,3.705-3.931,4.608
                        c-0.906,0.906-2.104,2.06-3.594,3.461c-1.494,1.401-2.759,2.622-3.798,3.661s-1.879,1.919-2.507,2.644
                        c-1.627,1.989-2.441,4.792-2.441,8.405L192.423,302.064L192.423,302.064z M185.031,332.169c-2.847,0-5.31-0.969-7.392-2.914
                        c-2.078-1.941-3.117-4.293-3.117-7.052c0-2.755,1.017-5.129,3.051-7.119s4.475-2.984,7.322-2.984s5.31,0.973,7.392,2.918
                        c2.078,1.945,3.117,4.293,3.117,7.048c0,2.759-1.017,5.133-3.051,7.122C190.319,331.178,187.879,332.169,185.031,332.169z"/>
                    </g>
                  </g>
                </g>
                <g id="XMLID_445_">
                  <g id="XMLID_446_">
                    <rect x="299.025" y="189.336" style="fill:#1D1D1B;" width="15.147" height="15.146"/>
                  </g>
                  <g id="XMLID_447_">
                    <rect x="329.319" y="189.336" style="fill:#1D1D1B;" width="15.147" height="15.146"/>
                  </g>
                  <g id="XMLID_448_">
                    <rect x="359.613" y="189.336" style="fill:#1D1D1B;" width="15.146" height="15.146"/>
                  </g>
                </g>
              </g>
            </g>
            <g>
            </g>
            <g>
            </g>
            <g>
            </g>
            <g>
            </g>
            <g>
            </g>
            <g>
            </g>
            <g>
            </g>
            <g>
            </g>
            <g>
            </g>
            <g>
            </g>
            <g>
            </g>
            <g>
            </g>
            <g>
            </g>
            <g>
            </g>
            <g>
            </g>
          </svg>
          <h2>Palestras</h2>
          <p>Palestras cenas , talks com profissionais da indústria</p>
        </div>
        <div class="networking">
          <svg version="1.1" :width="width" :height="height" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
            viewBox="0 0 512 512" style="enable-background:new 0 0 512 512;" xml:space="preserve">
            <circle style="fill:#273B7A;" cx="256" cy="256" r="256"/>
            <path style="fill:#121149;" d="M260.844,511.938c129.889-2.412,236.118-101.552,249.68-228.417l-85.533-85.532l-2.108,3.205
              l-58.606-58.609l-21.525-4.903l-68.003-69.299l-4.682,32.682l-86.159,19.634l-68.118,68.118l-4.31,16.331l-19.477,28.131
              l29.243,29.243l-69.844,39.979L260.844,511.938z"/>
            <path style="fill:#38C6D9;" d="M412.875,256c0-86.118-69.753-156.239-155.726-156.86v10.357
              c80.268,0.624,145.382,66.091,145.382,146.503S337.418,401.88,257.15,402.503v10.357C343.123,412.239,412.875,342.118,412.875,256z"
              />
            <path style="fill:#71E2EF;" d="M256,402.532c-80.798,0-146.532-65.734-146.532-146.532S175.202,109.468,256,109.468
              c0.386,0,0.765,0.026,1.15,0.029V99.14c-0.384-0.003-0.765-0.016-1.15-0.016c-86.502,0-156.875,70.373-156.875,156.875
              S169.498,412.875,256,412.875c0.384,0,0.765-0.012,1.15-0.016v-10.357C256.765,402.506,256.386,402.532,256,402.532z"/>
            <path style="fill:#FF7F4F;" d="M200.039,174.73c0-30.904,25.055-55.958,55.961-55.958s55.961,25.054,55.961,55.96L200.039,174.73z"
              />
            <path style="fill:#D35933;" d="M256.862,118.793v55.937h55.099C311.961,144.113,287.37,119.255,256.862,118.793z"/>
            <circle style="fill:#FF7F4F;" cx="256.896" cy="86.247" r="25.207"/>
            <path style="fill:#D35933;" d="M256.903,61.047c-0.014,0-0.028,0.002-0.041,0.002v50.412c0.014,0,0.028,0.002,0.041,0.002
              c13.922,0,25.207-11.285,25.207-25.207S270.826,61.047,256.903,61.047z"/>
            <path style="fill:#FF7F4F;" d="M200.039,430.264c0-30.904,25.055-55.958,55.961-55.958s55.961,25.054,55.961,55.96L200.039,430.264z
              "/>
            <path style="fill:#D35933;" d="M256.862,374.327v55.937h55.099C311.961,399.65,287.37,374.791,256.862,374.327z"/>
            <circle style="fill:#FF7F4F;" cx="256.896" cy="341.782" r="25.207"/>
            <path style="fill:#D35933;" d="M256.903,316.583c-0.014,0-0.028,0.002-0.041,0.002v50.412c0.014,0,0.028,0.002,0.041,0.002
              c13.922,0,25.207-11.285,25.207-25.207C282.11,327.868,270.826,316.583,256.903,316.583z"/>
            <path style="fill:#FFC61B;" d="M51.402,302.497c0-30.904,25.055-55.958,55.961-55.958s55.961,25.054,55.961,55.96L51.402,302.497z"
              />
            <path style="fill:#EAA22F;" d="M108.225,246.56v55.937h55.099C163.325,271.882,138.731,247.024,108.225,246.56z"/>
            <circle style="fill:#FFC61B;" cx="108.266" cy="214.023" r="25.207"/>
            <path style="fill:#EAA22F;" d="M108.266,188.814c-0.014,0-0.028,0.002-0.041,0.002v50.412c0.014,0,0.028,0.002,0.041,0.002
              c13.922,0,25.207-11.285,25.207-25.207C133.473,200.101,122.187,188.816,108.266,188.814z"/>
            <path style="fill:#FFC61B;" d="M348.677,302.497c0-30.904,25.055-55.958,55.961-55.958s55.961,25.054,55.961,55.96L348.677,302.497z
              "/>
            <path style="fill:#EAA22F;" d="M405.499,246.56v55.937h55.099C460.598,271.882,436.007,247.024,405.499,246.56z"/>
            <circle style="fill:#FFC61B;" cx="405.549" cy="214.023" r="25.207"/>
            <path style="fill:#EAA22F;" d="M405.54,188.814c-0.014,0-0.028,0.002-0.041,0.002v50.412c0.014,0,0.028,0.002,0.041,0.002
              c13.922,0,25.207-11.285,25.207-25.207C430.749,200.101,419.462,188.816,405.54,188.814z"/><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g>
          </svg>
          <h2>Networking</h2>
          <p>Disponibilizamos uma sala para os alunos do curso e diversos eventos técnicos e lúdidos como CTFs , LAN Parties</p>
        </div>
        <div class="plataformas">
          <svg version="1.1" :width="width" :height="height" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
            viewBox="0 0 511.999 511.999" style="enable-background:new 0 0 511.999 511.999;" xml:space="preserve" fill="#1935A1">
            <g>
              <g>
                <path d="M504.642,207.408l-44.917-4.491c-4.868-18.741-12.299-36.659-22.152-53.415l28.603-34.96
                  c2.657-3.248,2.423-7.983-0.546-10.95L408.409,46.37c-2.969-2.967-7.701-3.205-10.951-0.546l-34.96,28.603
                  c-16.757-9.853-34.673-17.285-53.415-22.152l-4.491-44.917c-0.418-4.178-3.933-7.359-8.13-7.359h-80.923
                  c-4.198,0-7.712,3.181-8.13,7.356l-4.491,44.917c-18.741,4.868-36.658,12.3-53.415,22.152l-34.96-28.603
                  c-3.248-2.658-7.983-2.423-10.951,0.546l-57.223,57.224c-2.969,2.969-3.203,7.702-0.546,10.95l28.603,34.96
                  c-9.853,16.755-17.284,34.673-22.152,53.415l-44.917,4.491C3.181,207.826,0,211.341,0,215.538v80.924
                  c0,4.197,3.181,7.713,7.358,8.13l44.917,4.491c4.868,18.741,12.299,36.659,22.152,53.415l-28.603,34.96
                  c-2.657,3.248-2.423,7.983,0.546,10.95l57.222,57.222c2.969,2.969,7.702,3.205,10.951,0.546l34.96-28.603
                  c16.757,9.853,34.673,17.285,53.415,22.152l4.491,44.917c0.418,4.175,3.932,7.356,8.13,7.356h80.923
                  c4.198,0,7.712-3.181,8.13-7.356l4.491-44.917c18.741-4.868,36.658-12.3,53.415-22.152l34.96,28.603
                  c3.247,2.657,7.982,2.422,10.951-0.546l57.222-57.222c2.969-2.969,3.203-7.702,0.546-10.95l-28.603-34.96
                  c9.853-16.755,17.284-34.673,22.152-53.415l44.917-4.491c4.177-0.417,7.358-3.933,7.358-8.13v-80.924
                  C512,211.341,508.819,207.826,504.642,207.408z M495.66,289.068l-43.308,4.331c-3.487,0.349-6.364,2.882-7.149,6.299
                  c-4.817,20.948-13.072,40.855-24.536,59.166c-1.859,2.971-1.617,6.797,0.602,9.509l27.579,33.709l-46.766,46.765l-33.708-27.58
                  c-2.711-2.221-6.538-2.462-9.509-0.601c-18.313,11.463-38.219,19.72-59.167,24.537c-3.416,0.785-5.95,3.661-6.299,7.149
                  l-4.332,43.308h-66.136l-4.331-43.308c-0.349-3.487-2.882-6.364-6.299-7.149c-20.947-4.817-40.854-13.072-59.167-24.537
                  c-2.97-1.861-6.797-1.617-9.509,0.601l-33.708,27.58l-46.766-46.765l27.579-33.709c2.219-2.713,2.462-6.538,0.602-9.509
                  c-11.463-18.311-19.72-38.217-24.536-59.167c-0.786-3.416-3.662-5.95-7.149-6.299l-43.308-4.331v-66.136l43.308-4.331
                  c3.487-0.349,6.364-2.882,7.149-6.299c4.817-20.948,13.072-40.855,24.536-59.167c1.86-2.971,1.617-6.797-0.602-9.509
                  l-27.579-33.709l46.766-46.765l33.708,27.58c2.711,2.22,6.539,2.462,9.509,0.601c18.313-11.463,38.219-19.72,59.167-24.537
                  c3.416-0.785,5.95-3.661,6.299-7.149l4.332-43.306h66.136l4.331,43.308c0.349,3.487,2.882,6.364,6.299,7.149
                  c20.947,4.817,40.854,13.072,59.166,24.537c2.971,1.861,6.797,1.618,9.509-0.601l33.708-27.581l46.766,46.765l-27.579,33.709
                  c-2.219,2.713-2.462,6.538-0.602,9.509c11.463,18.311,19.72,38.217,24.536,59.167c0.786,3.416,3.662,5.95,7.149,6.299
                  l43.307,4.331V289.068z"/>
              </g>
            </g>
            <g>
              <g>
                <path d="M256.002,171.575c-46.552,0-84.426,37.873-84.426,84.426s37.874,84.426,84.426,84.426
                  c46.552,0,84.426-37.873,84.426-84.426S302.554,171.575,256.002,171.575z M323.58,247.83h-34.136
                  c-0.715-20.686-4.154-41.364-10.591-55.958C302.719,200.403,320.462,221.895,323.58,247.83z M233.159,191.87
                  c-6.44,14.595-9.884,35.27-10.599,55.961h-34.135C191.542,221.893,209.288,200.398,233.159,191.87z M188.425,264.171h34.135
                  c0.715,20.692,4.16,41.366,10.603,55.962C209.289,311.605,191.542,290.11,188.425,264.171z M266.224,307.338
                  c-4.589,13.767-9.302,16.748-10.223,16.748c-0.921,0-5.633-2.98-10.223-16.748c-3.891-11.674-6.276-26.774-6.873-43.167h34.191
                  C272.499,280.563,270.116,295.664,266.224,307.338z M238.908,247.83c0.597-16.393,2.981-31.493,6.873-43.167
                  c4.588-13.767,9.301-16.748,10.222-16.748c0.92,0,5.633,2.98,10.223,16.748c3.891,11.674,6.276,26.774,6.873,43.167H238.908z
                  M278.849,320.13c6.439-14.594,9.881-35.271,10.595-55.959h34.135C320.462,290.107,302.718,311.6,278.849,320.13z"/>
              </g>
            </g>
            <g>
              <g>
                <path d="M256.002,77.89c-44.587,0-87.251,16.556-120.134,46.619c-32.668,29.866-52.966,70.484-57.154,114.373
                  c-0.429,4.491,2.865,8.481,7.356,8.91c4.521,0.431,8.482-2.865,8.91-7.358c7.955-83.35,77.179-146.204,161.022-146.204
                  c89.2,0,161.77,72.57,161.77,161.77s-72.57,161.77-161.77,161.77c-83.845,0-153.069-62.856-161.022-146.208
                  c-0.428-4.492-4.432-7.785-8.909-7.358c-4.493,0.429-7.786,4.417-7.358,8.91c4.188,43.889,24.484,84.509,57.152,114.376
                  c32.885,30.063,75.549,46.62,120.136,46.62c98.21,0,178.111-79.9,178.111-178.111S354.213,77.89,256.002,77.89z"/>
              </g>
            </g>
            <g>
              <g>
                <path d="M256.002,138.894c-25.202,0-49.22,7.89-69.452,22.818c-3.632,2.679-4.403,7.793-1.724,11.425
                  c2.68,3.632,7.794,4.404,11.424,1.724c17.405-12.839,38.066-19.626,59.753-19.626c55.563,0,100.766,45.203,100.766,100.766
                  c0,55.563-45.203,100.766-100.766,100.766s-100.766-45.203-100.766-100.766c0-21.688,6.787-42.351,19.629-59.756
                  c2.678-3.632,1.906-8.746-1.724-11.425c-3.633-2.679-8.745-1.907-11.425,1.723c-14.929,20.234-22.82,44.252-22.82,69.457
                  c0,64.573,52.534,117.106,117.106,117.106c64.572,0,117.106-52.533,117.106-117.106S320.574,138.894,256.002,138.894z"/>
              </g>
            </g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g>
          </svg>
          <h2>Plataformas</h2>
          <p>Plataformas , base de dados Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam vitae consectetur numquam commodi quasi dicta officiis dignissimos est nisi vero.</p>
        </div>
        <div class="workshops">
          <svg version="1.1" :width="width" :height="height" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
          viewBox="0 0 512 512" style="enable-background:new 0 0 512 512;" xml:space="preserve">
            <path style="fill:#25B6D2;" d="M0,260.908l174.648-81.136v38.568l-132.08,57.848v0.728l132.08,57.848v38.568L0,292.212V260.908z"/>
            <path style="fill:#415E72;" d="M201.6,387.9l77.864-263.8h36.752L238.4,387.9H201.6z"/>
            <path style="fill:#E04F5F;" d="M512,293.284L337.352,373.34v-38.568l134.992-57.848v-0.728L337.352,218.34v-38.568L512,259.828
              V293.284z"/>
            <g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g><g></g>
          </svg>
          <h2>Workshops</h2>
          <p>workshops tecnologias emergentes</p>
        </div>
      </div>
    </section>
    <section class="ourWork">
      <div class="work">
        <img src="@/assets/placeholder.jpg" alt="">
        <div class="text">
          <h1>Como podes ajudar?</h1>
          <p>Temos como objectivo apoiar os alunos do departamento de informática da Universidade de Évora, tanto a nivel escolar , como a nivel professional. Conseguimos isto através da organização de  workshops , talks com profissionais da industria , desenvolvimento de plataformas para os ajudar nos seus estudos e outros diversos eventos!</p>
          <div class="events">
            <EventCard />
            <EventCard />
            <EventCard />
          </div>
        </div>
      </div>
    </section>
    <section class="recrutamento">
      <div class="aboutUs">
        <div class="text">
          <h1>Who are we?</h1>
          
        </div>
       <img src="@/assets/placeholder.jpg" alt="">
      </div>
    </section>
    <section class="plataformas">
      <h1>Plataformas</h1>
      <p>De forma a ajudar os estudantes do curso de Engenharia Informática o NEEI disponibiliza </p>
    </section>
    <section class="noticias">
      <div class="noticiasPreview">
        <h1>Notícias</h1>
        <h2>Últimas noticias do NEEI. </h2>
      </div>
      
    </section>
    <Footer />

  
</template>

<script>
import Navbar from '@/components/Navbar.vue'
import EventCard from '@/components/EventCard.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  data() {
    return {
      height: '50px',
      width: '50px',
    }
  },
  components: {
    Navbar,
    EventCard,
    Footer,
  },
  created() {
    window.addEventListener('scroll', this.handleScroll);
    this.handleResize();
    window.addEventListener('resize', this.handleResize);
  },
  unmounted() {
    window.removeEventListener('scroll', this.handleScroll);
    window.removeEventListener('resize', this.handleResize);
  },
   methods: {
    scrollToElement(destination) {
      const element = document.querySelector(destination);
      if (element) {
        element.scrollIntoView({behavior: 'smooth'});
      }
    },
    getImgURL(image) {
        return require('../assets/' + image);
    },
    handleScroll () {
      window.pageYOffset >= 250 ? this.isAtTop = false : this.isAtTop = true;
    },
    handleResize () {
      this.mobileMode = window.innerWidth <= 1015;
      if(!this.mobileMode) {
        this.activatedNavbar = false;
      }
    },
  },
};
</script>

<style lang="scss" scoped>

$informaticaBlue: #1935A1;
$informaticaLightBlue: lighten($color: $informaticaBlue, $amount: 62%);
$mirtiloAzul: lighten($color: $informaticaBlue, $amount: 40%);


section {
  padding: 20px;
}

.heroContent {
  height: 100vh;
  width: 100%;
  display: flex;
  justify-content: space-around;
  align-items: center;
  overflow: hidden;
  max-width: 100%;
  .textArea {
    display: flex;
    width: 40%;
    justify-content: left;
    align-items: left;
    flex-direction: column;
    margin-left: 40px;
    .slogan {
      font-size: 2.5vw;
      margin: 10px 0px;
      text-transform: uppercase;
    }
    
    .heroText {
      width: 85%;
    }
    
    button {
      max-width: 300px;
      position: relative;
      display: inline-block;
      text-align: center;
      text-transform: uppercase; 
      padding: 15px;
      margin: 30px 25px 0 0 ;
      font-size: 100% + 10%;
      font-weight: 600;
      border-radius: 5px;
      border: none;
      color: $informaticaBlue;
      background-color: white;
      transition: all 0.5s;
      &::before {
        position: absolute;
        content:"";
        border-radius: 5px;
        border-top: 5px solid lighten($informaticaBlue, 5%);
        border-left: 5px solid lighten($informaticaBlue, 5%);	
        border-right: 5px solid darken($informaticaBlue, 5%);
        border-bottom: 5px solid darken($informaticaBlue, 5%);
        top: 0px;
        right: 0px;
        bottom: 0px;
        left: 0px;	
        transition: 0.5s;
      }
      &:hover {
        box-shadow: 7px 7px darken($informaticaBlue, 10%), -7px -7px lighten($informaticaBlue, 10%);
        background-color: $informaticaBlue;
        color: #f7f7f7;
        cursor: pointer;
          &::before {
          border: 0px;
        }
      }
    }
    .socio {
      background: #f7f7f7;
      color: $informaticaBlue;
    }
    .socio:hover {
      box-shadow: 7px 7px darken($informaticaBlue, 10%), -7px -7px lighten($informaticaBlue, 10%);
      background-color: $informaticaBlue;
      color: #f7f7f7;
      cursor: pointer;
    }
  }
  .heroImage {
    width: 48%;
    overflow-x: none;
  }
}

.features {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  background-color: $informaticaLightBlue;

  h1 {
    font-size: 48px;
    margin-bottom: 20px;
  }

  .subtitle {
    text-align: center;
    margin-top: 0;
    margin-bottom: 100px;
    width: 50%;
  }

  .feature {
    display: flex;
    justify-content: center;
    align-items: center;

    div {
      width: 20%;
      height: 300px;
      display: flex;
      align-items: center;
      flex-direction: column;
      margin: 20px 30px 20px 30px;
      padding: 10px;
    }
  }
}

.ourWork {
  padding: 20px;
  height: 100vh;
  .work {
    display: flex;
    img {
      margin-right: 30px;
      width: 40%
    
    }

    .events {
      display: flex;
    }
    .text {
      display: flex;
      flex-direction: column;
      h1 {
        text-transform: uppercase;
      }
    }
  }
}
.recrutamento {
  padding: 20px;
  height: 100vh;
  .aboutUs {
    display: flex;
    img {
      margin-left: 30px;
      width: 50%
    
    }
    .text {
      display: flex;
      flex-direction: column;
      h1 {
        text-transform: uppercase;
      }
    }
  }
}
.plataformas {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  h1 {
    font-size: 80px;
  }
  .plataformaCards {
    display: flex;
  }
}
.noticias {
  h1 {
    font-size: 80px;
  }
  .noticiasPreview {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    .carrossel {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
  }
}
</style>
