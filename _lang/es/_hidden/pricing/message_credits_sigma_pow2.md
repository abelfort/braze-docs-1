---
nav_title: Créditos de los mensajes - Sigma
permalink: "/message_credits_sigma_pow2/"
hidden: true
noindex: true
hide_toc: true
---

# Créditos de los mensajes - Sigma (Confidencial)

> Créditos de mensajes es la estructura de paquetes multicanal de Braze para nuestras ofertas nativas de SMS, MMS y WhatsApp. Los créditos de mensajes proporcionan una experiencia flexible y transparente al aprovechar los canales de mensajería Braze. Los créditos te dan acceso a cualquiera de los canales presentados en la tabla de esta página.

{% alert note %}
Los distintos canales tendrán distintas unidades de medida para informar.<br><br>
<b>WhatsApp:</b> Conversaciones<br>
<b>SMS:</b> Segmentos<br>
<b>MMS:</b> Segmentos<br><br>
En otras palabras, los créditos por mensajes de WhatsApp se calcularán sobre los inicios de conversación, y los créditos por mensajes SMS y MMS se calcularán sobre los segmentos enviados.
<br><br>
Por último, las tarifas de operador se facturan por separado (a mes vencido) y no se consideran parte de este SKU de Créditos para mensajes.
{% endalert %}

## Definiciones

Las definiciones de las columnas son las siguientes:

|---------|-------------------------------------------------|
| **Ratio de crédito del canal** | Importe del crédito base para cada canal |
| **Destino** | Región final específica, país o tipo de mensaje que se envía a través de la plataforma Braze |
| **Multiplicador** | Escala al coeficiente de crédito del canal, según el precio del destino específico |
| **Créditos por 1 envío** | Número exacto de Crédito de mensajes para enviar un mensaje<br> (créditos por mensaje = ratio de créditos del canal x multiplicador de destino) |
{: .reset-td-br-1 .reset-td-br-2 role="presentation" }


## Tabla de relación de créditos para créditos de mensajes - Sigma

{% details Haz clic para ampliar %}
<table>
    <colgroup>
        <col span="4" style="background-color:background-color:#FFFFFF;">
        <col style="background-color:#f0f0f5">
    </colgroup>
    <tr>
        <th><b>Canal</b></th>
        <th><b>Ratio de crédito del canal</b></th>
        <th><b>Destino</b></th>
        <th><b>Multiplicador</b></th>
        <th class="credits-column"><b>Créditos por 1 envío</b></th>
    </tr>
    <tbody><tr>
        <td>SMS - US / CA</td>
        <td>1</td>
        <td>Estados Unidos</td>
        <td>1.00</td>
        <td>1.00</td>
    </tr>
    <tr>
        <td>SMS - US / CA</td>
        <td>1</td>
        <td>Estados Unidos Llamada gratuita</td>
        <td>1.50</td>
        <td>1.50</td>
    </tr>
    <tr>
        <td>SMS - US / CA</td>
        <td>1</td>
        <td>Canadá</td>
        <td>1.00</td>
        <td>1.00</td>
    </tr>
    <tr>
        <td>SMS - US / CA</td>
        <td>1</td>
        <td>Llamada gratuita a Canadá</td>
        <td>1.30</td>
        <td>1.30</td>
    </tr>
    <tr>
        <td>MMS - US / CA</td>
        <td>3</td>
        <td>Estados Unidos</td>
        <td>1.00</td>
        <td>3.00</td>
    </tr>
    <tr>
        <td>MMS - US / CA</td>
        <td>3</td>
        <td>Estados Unidos Llamada gratuita</td>
        <td>2.00</td>
        <td>6.00</td>
    </tr>
    <tr>
        <td>MMS - US / CA</td>
        <td>3</td>
        <td>Código largo de Canadá</td>
        <td>1.50</td>
        <td>4.50</td>
    </tr>
    <tr>
        <td>MMS - US / CA</td>
        <td>3</td>
        <td>Código abreviado de Canadá</td>
        <td>4.00</td>
        <td>12.00</td>
    </tr>
    <tr>
        <td>MMS - US / CA</td>
        <td>3</td>
        <td>Llamada gratuita a Canadá</td>
        <td>1.30</td>
        <td>3.90</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Abjasia</td>
        <td>0.62</td>
        <td>4.65</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Afganistán</td>
        <td>9.47</td>
        <td>71.03</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Albania</td>
        <td>2.29</td>
        <td>17.18</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Argelia</td>
        <td>5.23</td>
        <td>39.23</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Samoa Estadounidense</td>
        <td>4.74</td>
        <td>35.55</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Andorra</td>
        <td>3.32</td>
        <td>24.90</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Angola</td>
        <td>2.24</td>
        <td>16.80</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Anguila</td>
        <td>3.33</td>
        <td>24.98</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Antigua y Barbuda</td>
        <td>2.47</td>
        <td>18.53</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Argentina</td>
        <td>1.02</td>
        <td>7.65</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Armenia</td>
        <td>3.49</td>
        <td>26.18</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Aruba</td>
        <td>2.61</td>
        <td>19.58</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Australia SMS</td>
        <td>0.36</td>
        <td>2.70</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Australia MMS</td>
        <td>3.10</td>
        <td>23.25</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Austria</td>
        <td>1.77</td>
        <td>13.28</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Azerbaiyán</td>
        <td>9.77</td>
        <td>73.28</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Bahamas</td>
        <td>1.23</td>
        <td>9.23</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Bahréin</td>
        <td>0.92</td>
        <td>6.90</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Bangladés</td>
        <td>5.81</td>
        <td>43.58</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Barbados</td>
        <td>3.09</td>
        <td>23.18</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Bielorrusia</td>
        <td>6.35</td>
        <td>47.63</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Bélgica</td>
        <td>2.40</td>
        <td>18.00</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Belice</td>
        <td>6.90</td>
        <td>51.75</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Benín</td>
        <td>3.64</td>
        <td>27.30</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Bermuda</td>
        <td>2.99</td>
        <td>22.43</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Bután</td>
        <td>10.10</td>
        <td>75.75</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Bolivia</td>
        <td>3.66</td>
        <td>27.45</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Bosnia y Herzegovina</td>
        <td>2.12</td>
        <td>15.90</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Botsuana</td>
        <td>2.52</td>
        <td>18.90</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Brasil</td>
        <td>0.25</td>
        <td>1.88</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Brunéi</td>
        <td>0.50</td>
        <td>3.75</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Bulgaria</td>
        <td>2.70</td>
        <td>20.25</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Burkina Faso</td>
        <td>3.35</td>
        <td>25.13</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Burundi</td>
        <td>9.47</td>
        <td>71.03</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Camboya</td>
        <td>4.30</td>
        <td>32.25</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Camerún</td>
        <td>3.49</td>
        <td>26.18</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Cabo Verde</td>
        <td>3.66</td>
        <td>27.45</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Caribe Países Bajos</td>
        <td>2.17</td>
        <td>16.28</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Islas Caimán</td>
        <td>3.37</td>
        <td>25.28</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>República Centroafricana</td>
        <td>3.07</td>
        <td>23.03</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Chad</td>
        <td>7.30</td>
        <td>54.75</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Chile</td>
        <td>1.64</td>
        <td>12.30</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>China</td>
        <td>0.64</td>
        <td>4.80</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Colombia</td>
        <td>0.02</td>
        <td>0.15</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Comoras</td>
        <td>6.19</td>
        <td>46.43</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Congo</td>
        <td>5.04</td>
        <td>37.80</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Islas Cook</td>
        <td>3.52</td>
        <td>26.40</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Costa Rica</td>
        <td>1.06</td>
        <td>7.95</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Croacia</td>
        <td>2.31</td>
        <td>17.33</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Cuba</td>
        <td>2.12</td>
        <td>15.90</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Curazao</td>
        <td>0.99</td>
        <td>7.43</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Chipre</td>
        <td>2.18</td>
        <td>16.35</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>República Checa</td>
        <td>1.01</td>
        <td>7.58</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Dinamarca</td>
        <td>1.01</td>
        <td>7.58</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Yibuti</td>
        <td>4.09</td>
        <td>30.68</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Dominica</td>
        <td>3.79</td>
        <td>28.43</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>República Dominicana</td>
        <td>1.29</td>
        <td>9.68</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>RD Congo</td>
        <td>5.77</td>
        <td>43.28</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Ecuador</td>
        <td>2.76</td>
        <td>20.70</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Egipto</td>
        <td>2.43</td>
        <td>18.23</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>El Salvador</td>
        <td>2.45</td>
        <td>18.38</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Guinea Ecuatorial</td>
        <td>4.36</td>
        <td>32.70</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Eritrea</td>
        <td>2.48</td>
        <td>18.60</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Estonia</td>
        <td>2.41</td>
        <td>18.08</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Eswatini</td>
        <td>0.58</td>
        <td>4.35</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Etiopía</td>
        <td>8.63</td>
        <td>64.73</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Islas Malvinas</td>
        <td>3.43</td>
        <td>25.73</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Islas Feroe</td>
        <td>1.70</td>
        <td>12.75</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Fiyi</td>
        <td>4.16</td>
        <td>31.20</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Finlandia</td>
        <td>1.46</td>
        <td>10.95</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Francia</td>
        <td>0.98</td>
        <td>7.35</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Guyana Francesa</td>
        <td>4.64</td>
        <td>34.80</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Polinesia Francesa</td>
        <td>4.53</td>
        <td>33.98</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Gabón</td>
        <td>6.64</td>
        <td>49.80</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Gambia</td>
        <td>4.18</td>
        <td>31.35</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Georgia</td>
        <td>2.63</td>
        <td>19.73</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Alemania</td>
        <td>1.88</td>
        <td>14.10</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Ghana</td>
        <td>2.26</td>
        <td>16.95</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Gibraltar</td>
        <td>2.75</td>
        <td>20.63</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Grecia</td>
        <td>0.99</td>
        <td>7.43</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Groenlandia</td>
        <td>1.03</td>
        <td>7.73</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Granada</td>
        <td>4.09</td>
        <td>30.68</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Guadalupe</td>
        <td>3.40</td>
        <td>25.50</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Guam</td>
        <td>1.73</td>
        <td>12.98</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Guatemala</td>
        <td>3.20</td>
        <td>24.00</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Guernsey</td>
        <td>0.87</td>
        <td>6.53</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Guinea</td>
        <td>3.82</td>
        <td>28.65</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Guinea-Bissau</td>
        <td>3.97</td>
        <td>29.78</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Guyana</td>
        <td>4.50</td>
        <td>33.75</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Haití</td>
        <td>5.94</td>
        <td>44.55</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Honduras</td>
        <td>2.13</td>
        <td>15.98</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Hong Kong</td>
        <td>1.35</td>
        <td>10.13</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Hungría</td>
        <td>1.91</td>
        <td>14.33</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Islandia</td>
        <td>1.75</td>
        <td>13.13</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>India</td>
        <td>1.00</td>
        <td>7.50</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Indonesia</td>
        <td>6.63</td>
        <td>49.73</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Irán</td>
        <td>6.25</td>
        <td>46.88</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Irak</td>
        <td>4.79</td>
        <td>35.93</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Irlanda</td>
        <td>1.31</td>
        <td>9.83</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Isla de Man</td>
        <td>0.81</td>
        <td>6.08</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Israel</td>
        <td>3.74</td>
        <td>28.05</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Italia</td>
        <td>0.78</td>
        <td>5.85</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Costa de Marfil</td>
        <td>2.48</td>
        <td>18.60</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Jamaica</td>
        <td>3.05</td>
        <td>22.88</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Japón</td>
        <td>1.02</td>
        <td>7.65</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Jersey</td>
        <td>0.70</td>
        <td>5.25</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Jordania</td>
        <td>5.56</td>
        <td>41.70</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Kazajistán</td>
        <td>5.52</td>
        <td>41.40</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Kenia</td>
        <td>2.62</td>
        <td>19.65</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Kiribati</td>
        <td>3.67</td>
        <td>27.53</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>República de Corea</td>
        <td>0.69</td>
        <td>5.18</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Kosovo</td>
        <td>0.97</td>
        <td>7.28</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Kuwait</td>
        <td>3.34</td>
        <td>25.05</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Kirguistán</td>
        <td>6.12</td>
        <td>45.90</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>RDP Lao</td>
        <td>1.54</td>
        <td>11.55</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Letonia</td>
        <td>1.80</td>
        <td>13.50</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Líbano</td>
        <td>3.07</td>
        <td>23.03</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Lesoto</td>
        <td>5.14</td>
        <td>38.55</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Liberia</td>
        <td>3.47</td>
        <td>26.03</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Libia</td>
        <td>8.17</td>
        <td>61.28</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Liechtenstein</td>
        <td>0.84</td>
        <td>6.30</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Lituania</td>
        <td>1.37</td>
        <td>10.28</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Luxemburgo</td>
        <td>1.86</td>
        <td>13.95</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Macao</td>
        <td>1.49</td>
        <td>11.18</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Macedonia</td>
        <td>1.88</td>
        <td>14.10</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Madagascar</td>
        <td>9.40</td>
        <td>70.50</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Malaui</td>
        <td>5.72</td>
        <td>42.90</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Malasia</td>
        <td>1.47</td>
        <td>11.03</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Maldivas</td>
        <td>1.80</td>
        <td>13.50</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Mali</td>
        <td>3.97</td>
        <td>29.78</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Malta</td>
        <td>1.64</td>
        <td>12.30</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Islas Marshall</td>
        <td>4.00</td>
        <td>30.00</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Martinica</td>
        <td>3.33</td>
        <td>24.98</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Mauritania</td>
        <td>6.51</td>
        <td>48.83</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Mauricio</td>
        <td>4.02</td>
        <td>30.15</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Mayotte</td>
        <td>2.33</td>
        <td>17.48</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>México</td>
        <td>0.27</td>
        <td>2.03</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Micronesia</td>
        <td>1.85</td>
        <td>13.88</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Moldavia</td>
        <td>1.59</td>
        <td>11.93</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Mónaco</td>
        <td>4.68</td>
        <td>35.10</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Mongolia</td>
        <td>7.03</td>
        <td>52.73</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Montenegro</td>
        <td>2.87</td>
        <td>21.53</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Montserrat</td>
        <td>2.77</td>
        <td>20.78</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Marruecos</td>
        <td>2.64</td>
        <td>19.80</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Mozambique</td>
        <td>2.76</td>
        <td>20.70</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Myanmar</td>
        <td>5.84</td>
        <td>43.80</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Namibia</td>
        <td>1.58</td>
        <td>11.85</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Nauru</td>
        <td>1.12</td>
        <td>8.40</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Nepal</td>
        <td>3.82</td>
        <td>28.65</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Países Bajos</td>
        <td>1.65</td>
        <td>12.38</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Nueva Caledonia</td>
        <td>4.44</td>
        <td>33.30</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Nueva Zelanda</td>
        <td>1.92</td>
        <td>14.40</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Nicaragua</td>
        <td>1.95</td>
        <td>14.63</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Níger</td>
        <td>7.49</td>
        <td>56.18</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Nigeria</td>
        <td>5.01</td>
        <td>37.58</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Niue</td>
        <td>4.86</td>
        <td>36.45</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Isla Norfolk</td>
        <td>0.71</td>
        <td>5.33</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Macedonia del Norte</td>
        <td>0.34</td>
        <td>2.55</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Norte de Chipre</td>
        <td>0.20</td>
        <td>1.50</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Noruega</td>
        <td>1.05</td>
        <td>7.88</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Omán</td>
        <td>3.60</td>
        <td>27.00</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Pakistán</td>
        <td>7.46</td>
        <td>55.95</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Palaos</td>
        <td>2.52</td>
        <td>18.90</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Territorio Palestino</td>
        <td>7.68</td>
        <td>57.60</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Panamá</td>
        <td>2.23</td>
        <td>16.73</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Papúa Nueva Guinea</td>
        <td>19.01</td>
        <td>142.58</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Paraguay</td>
        <td>1.84</td>
        <td>13.80</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Perú</td>
        <td>0.81</td>
        <td>6.08</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Filipinas</td>
        <td>0.28</td>
        <td>2.10</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Polonia</td>
        <td>0.52</td>
        <td>3.90</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Portugal</td>
        <td>0.60</td>
        <td>4.50</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Puerto Rico</td>
        <td>1.06</td>
        <td>7.95</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Catar</td>
        <td>0.52</td>
        <td>3.90</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Reunión/Mayotte</td>
        <td>4.82</td>
        <td>36.15</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Rumanía</td>
        <td>1.06</td>
        <td>7.95</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Rusia</td>
        <td>9.54</td>
        <td>71.55</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Ruanda</td>
        <td>4.66</td>
        <td>34.95</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>San Cristóbal y Nieves</td>
        <td>0.92</td>
        <td>6.90</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Santa Lucía</td>
        <td>1.07</td>
        <td>8.03</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>San Pedro y Miquelón</td>
        <td>2.31</td>
        <td>17.33</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>San Vicente y las Granadinas</td>
        <td>1.06</td>
        <td>7.95</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Samoa</td>
        <td>4.68</td>
        <td>35.10</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>San Marino</td>
        <td>2.76</td>
        <td>20.70</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Santo Tomé y Príncipe</td>
        <td>3.29</td>
        <td>24.68</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Arabia Saudí</td>
        <td>1.91</td>
        <td>14.33</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Senegal</td>
        <td>5.15</td>
        <td>38.63</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Serbia</td>
        <td>6.09</td>
        <td>45.68</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Seychelles</td>
        <td>0.94</td>
        <td>7.05</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Sierra Leona</td>
        <td>4.73</td>
        <td>35.48</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Singapur</td>
        <td>0.70</td>
        <td>5.25</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>San Martín</td>
        <td>0.16</td>
        <td>1.20</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Eslovaquia</td>
        <td>2.23</td>
        <td>16.73</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Eslovenia</td>
        <td>3.76</td>
        <td>28.20</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Islas Salomón</td>
        <td>2.09</td>
        <td>15.68</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Somalia</td>
        <td>4.74</td>
        <td>35.55</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Sudáfrica</td>
        <td>0.32</td>
        <td>2.40</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Osetia del Sur</td>
        <td>2.05</td>
        <td>15.38</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Sudán del Sur</td>
        <td>0.80</td>
        <td>6.00</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>España</td>
        <td>0.80</td>
        <td>6.00</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Sri Lanka</td>
        <td>5.60</td>
        <td>42.00</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Sudán</td>
        <td>4.15</td>
        <td>31.13</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Surinam</td>
        <td>3.28</td>
        <td>24.60</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Suazilandia</td>
        <td>2.32</td>
        <td>17.40</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Suecia</td>
        <td>0.86</td>
        <td>6.45</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Suiza</td>
        <td>0.60</td>
        <td>4.50</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Siria</td>
        <td>7.86</td>
        <td>58.95</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Taiwán</td>
        <td>0.84</td>
        <td>6.30</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Tayikistán</td>
        <td>11.35</td>
        <td>85.13</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Tanzania</td>
        <td>5.38</td>
        <td>40.35</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Tailandia</td>
        <td>0.36</td>
        <td>2.70</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Timor-Leste</td>
        <td>2.86</td>
        <td>21.45</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Togo</td>
        <td>3.84</td>
        <td>28.80</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Tonga</td>
        <td>3.14</td>
        <td>23.55</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Trinidad y Tobago</td>
        <td>3.02</td>
        <td>22.65</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Túnez</td>
        <td>7.06</td>
        <td>52.95</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Turquía</td>
        <td>0.77</td>
        <td>5.78</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Turkmenistán</td>
        <td>5.04</td>
        <td>37.80</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Islas Turcas y Caicos</td>
        <td>3.38</td>
        <td>25.35</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Tuvalu</td>
        <td>3.36</td>
        <td>25.20</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Uganda</td>
        <td>4.05</td>
        <td>30.38</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Ucrania</td>
        <td>2.86</td>
        <td>21.45</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Emiratos Árabes Unidos</td>
        <td>1.24</td>
        <td>9.30</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Reino Unido</td>
        <td>0.65</td>
        <td>4.88</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Desconocido</td>
        <td>3.92</td>
        <td>29.40</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Uruguay</td>
        <td>2.15</td>
        <td>16.13</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Uzbekistán</td>
        <td>6.88</td>
        <td>51.60</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Vanuatu</td>
        <td>4.18</td>
        <td>31.35</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Venezuela</td>
        <td>2.15</td>
        <td>16.13</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Vietnam</td>
        <td>3.05</td>
        <td>22.88</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Islas Vírgenes Británicas</td>
        <td>4.73</td>
        <td>35.48</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Islas Vírgenes, U.S.</td>
        <td>0.50</td>
        <td>3.75</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Wallis y Futuna</td>
        <td>2.77</td>
        <td>20.78</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Yemen</td>
        <td>6.03</td>
        <td>45.23</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Zambia</td>
        <td>6.76</td>
        <td>50.70</td>
    </tr>
    <tr>
        <td>SMS / MMS - Global</td>
        <td>7.5</td>
        <td>Zimbabue</td>
        <td>3.55</td>
        <td>26.63</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autenticación en Argentina</td>
        <td>0.95</td>
        <td>7.13</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en Argentina</td>
        <td>1.65</td>
        <td>12.38</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en Argentina</td>
        <td>0.90</td>
        <td>6.75</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autenticación en Brasil</td>
        <td>0.85</td>
        <td>6.38</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en Brasil</td>
        <td>1.65</td>
        <td>12.38</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en Brasil</td>
        <td>0.21</td>
        <td>1.58</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autenticación en Chile</td>
        <td>1.40</td>
        <td>10.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en Chile</td>
        <td>2.35</td>
        <td>17.63</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en Chile</td>
        <td>0.53</td>
        <td>3.98</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autenticación en Colombia</td>
        <td>0.20</td>
        <td>1.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en Colombia</td>
        <td>0.35</td>
        <td>2.63</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en Colombia</td>
        <td>0.01</td>
        <td>0.08</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autentificación de Egipto</td>
        <td>1.65</td>
        <td>12.38</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en Egipto</td>
        <td>2.85</td>
        <td>21.38</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en Egipto</td>
        <td>0.14</td>
        <td>1.05</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autenticación en Francia</td>
        <td>1.85</td>
        <td>13.88</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en Francia</td>
        <td>3.80</td>
        <td>28.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en Francia</td>
        <td>0.80</td>
        <td>6.00</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autentificación en Alemania</td>
        <td>2.05</td>
        <td>15.38</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en Alemania</td>
        <td>3.60</td>
        <td>27.00</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en Alemania</td>
        <td>1.46</td>
        <td>10.95</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autentificación en India</td>
        <td>0.04</td>
        <td>0.30</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autenticación en India - Internacional</td>
        <td>0.74</td>
        <td>5.55</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en India</td>
        <td>0.25</td>
        <td>1.88</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en India</td>
        <td>0.04</td>
        <td>0.30</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autenticación en Indonesia</td>
        <td>0.80</td>
        <td>6.00</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autenticación en Indonesia - Internacional</td>
        <td>3.61</td>
        <td>27.08</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en Indonesia</td>
        <td>1.10</td>
        <td>8.25</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en Indonesia</td>
        <td>0.55</td>
        <td>4.13</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autentificación de Israel</td>
        <td>0.45</td>
        <td>3.38</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en Israel</td>
        <td>0.95</td>
        <td>7.13</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en Israel</td>
        <td>0.14</td>
        <td>1.05</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autentificación en Italia</td>
        <td>1.00</td>
        <td>7.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en Italia</td>
        <td>1.85</td>
        <td>13.88</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en Italia</td>
        <td>0.80</td>
        <td>6.00</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autenticación en Malasia</td>
        <td>0.50</td>
        <td>3.75</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en Malasia</td>
        <td>2.30</td>
        <td>17.25</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en Malasia</td>
        <td>0.37</td>
        <td>2.78</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autenticación en México</td>
        <td>0.65</td>
        <td>4.88</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en México</td>
        <td>1.15</td>
        <td>8.63</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en México</td>
        <td>0.27</td>
        <td>2.03</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autenticación de los Países Bajos</td>
        <td>1.90</td>
        <td>14.25</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en Países Bajos</td>
        <td>4.25</td>
        <td>31.88</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en Países Bajos</td>
        <td>1.33</td>
        <td>9.98</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autenticación en Nigeria</td>
        <td>0.75</td>
        <td>5.63</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en Nigeria</td>
        <td>1.35</td>
        <td>10.13</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en Nigeria</td>
        <td>0.18</td>
        <td>1.35</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autenticación en Norteamérica</td>
        <td>0.35</td>
        <td>2.63</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en Norteamérica</td>
        <td>0.65</td>
        <td>4.88</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en Norteamérica</td>
        <td>0.11</td>
        <td>0.83</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Otra autenticación</td>
        <td>0.80</td>
        <td>6.00</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en otras regiones</td>
        <td>1.60</td>
        <td>12.00</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en otras regiones</td>
        <td>0.20</td>
        <td>1.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autentificación de Pakistán</td>
        <td>0.60</td>
        <td>4.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en Pakistán</td>
        <td>1.25</td>
        <td>9.38</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en Pakistán</td>
        <td>0.14</td>
        <td>1.05</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autenticación en Perú</td>
        <td>1.00</td>
        <td>7.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en Perú</td>
        <td>1.85</td>
        <td>13.88</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en Perú</td>
        <td>0.53</td>
        <td>3.98</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autenticación en el resto de África</td>
        <td>0.40</td>
        <td>3.00</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en el resto de África</td>
        <td>0.60</td>
        <td>4.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en el resto de África</td>
        <td>0.16</td>
        <td>1.20</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autenticación en el resto de Asia-Pacífico</td>
        <td>1.15</td>
        <td>8.63</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en el resto de Asia Pacífico</td>
        <td>1.95</td>
        <td>14.63</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en el resto de Asia-Pacífico</td>
        <td>0.42</td>
        <td>3.15</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autenticación en el resto de Europa Central y Oriental</td>
        <td>1.50</td>
        <td>11.25</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en el resto de Europa Central y Oriental</td>
        <td>2.30</td>
        <td>17.25</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en el resto de Europa Central y Oriental</td>
        <td>0.94</td>
        <td>7.05</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autenticación en el resto de Latinoamérica</td>
        <td>1.20</td>
        <td>9.00</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en el resto de Latinoamérica</td>
        <td>1.95</td>
        <td>14.63</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en el resto de Latinoamérica</td>
        <td>0.30</td>
        <td>2.25</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autenticación en el resto de Oriente Medio</td>
        <td>0.45</td>
        <td>3.38</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en el resto de Oriente Medio</td>
        <td>0.90</td>
        <td>6.75</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en el resto de Oriente Medio</td>
        <td>0.42</td>
        <td>3.15</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autenticación en el resto de Europa Occidental</td>
        <td>1.00</td>
        <td>7.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en el resto de Europa Occidental</td>
        <td>1.55</td>
        <td>11.63</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en el resto de Europa Occidental</td>
        <td>0.80</td>
        <td>6.00</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autentificación de Rusia</td>
        <td>1.15</td>
        <td>8.63</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en Rusia</td>
        <td>2.15</td>
        <td>16.13</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en Rusia</td>
        <td>1.06</td>
        <td>7.95</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autentificación en Arabia Saudí</td>
        <td>0.60</td>
        <td>4.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en Arabia Saudí</td>
        <td>1.10</td>
        <td>8.25</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en Arabia Saudí</td>
        <td>0.31</td>
        <td>2.33</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autenticación en Sudáfrica</td>
        <td>0.50</td>
        <td>3.75</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en Sudáfrica</td>
        <td>1.00</td>
        <td>7.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en Sudáfrica</td>
        <td>0.20</td>
        <td>1.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autentificación en España</td>
        <td>0.90</td>
        <td>6.75</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en España</td>
        <td>1.65</td>
        <td>12.38</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en España</td>
        <td>0.53</td>
        <td>3.98</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autentificación de Turquía</td>
        <td>0.20</td>
        <td>1.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en Turquía</td>
        <td>0.30</td>
        <td>2.25</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en Turquía</td>
        <td>0.14</td>
        <td>1.05</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autenticación en Emiratos Árabes Unidos</td>
        <td>0.45</td>
        <td>3.38</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en Emiratos Árabes Unidos</td>
        <td>0.90</td>
        <td>6.75</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en Emiratos Árabes Unidos</td>
        <td>0.42</td>
        <td>3.15</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Autentificación en el Reino Unido</td>
        <td>0.95</td>
        <td>7.13</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Marketing en Reino Unido</td>
        <td>1.40</td>
        <td>10.50</td>
    </tr>
    <tr>
        <td>WhatsApp</td>
        <td>7.5</td>
        <td>Servicios públicos en Reino Unido</td>
        <td>0.58</td>
        <td>4.35</td>
    </tr>
    <tr>
        <td>LINE</td>
        <td>1</td>
        <td>Todas las regiones</td>
        <td>0.15</td>
        <td>0.15</td>
    </tr>
    </tbody></table>
{: .reset-td-br-1 .reset-td-br-2 role="presentation" }
{% enddetails %}

------

## Detalles del canal SMS/MMS

### Segmentos SMS

Los segmentos del mensaje SMS son la forma en que la industria del SMS cuenta los mensajes. Un segmento del mensaje es una agrupación de hasta un número definido de caracteres (160 para la codificación GSM-7; 67 para la codificación UCS-2) que se enviarán en un único envío SMS. Si envías un SMS con 161 caracteres utilizando la codificación GSM-7, verás que se han enviado dos (2) segmentos del mensaje. El envío de varios segmentos del mensaje conllevará cargos adicionales.

### Segmentos MMS

Para MMS, el límite de mensajes es de 5 MB (esto incluye el activo multimedia y el tamaño del cuerpo del mensaje). Para estar más seguro, Braze recomienda no superar los 600 KB para tu activo multimedia, incluyendo también el cuerpo del mensaje.

## Detalles del canal WhatsApp

WhatsApp es un canal centrado en la mensajería bidireccional y, por tanto, se centra en las Conversaciones (en lugar del número de mensajes individuales). Una Conversación es un hilo de 24 horas entre una empresa y un usuario final.

### Definiciones del tipo de conversación

**Conversaciones sobre marketing:** Conversaciones iniciadas por la empresa que te habilitan para alcanzar una amplia gama de objetivos, desde generar notoriedad hasta impulsar las ventas y reorientar a los clientes. Algunos ejemplos son anuncios de nuevos productos, servicios o características, promociones/ofertas específicas y recordatorios de abandono del carrito de compras.

**Conversaciones sobre servicios públicos:** Conversaciones iniciadas por la empresa que te habilitan para hacer un seguimiento de las acciones o peticiones de los usuarios. Algunos ejemplos son la confirmación de adhesión voluntaria, la gestión de pedidos/entregas (e.g., actualización de entregas), actualizaciones de cuentas o alertas (e.g., recordatorio de pago), o cuestionarios de opinión.

**Conversaciones de autentificación:** Te habilita para autenticar usuarios con códigos de acceso de un solo uso, potencialmente en múltiples pasos del proceso de iniciar sesión (e.g., verificación de cuenta, recuperación de cuenta, retos de integridad).

{% alert note %}
Las conversaciones de autenticación sólo se admitirán caso por caso y Braze no puede garantizar SLA específicos. Además, Braze no admite la generación de PIN.
{% endalert %}

**Conversaciones sobre servicio:** Conversaciones iniciadas por el usuario a las que se responde con un mensaje no planificado.

{% alert note %}
A partir del 1 de noviembre de 2024, las conversiones de tipo servicio son gratuitas y no se deducirán de las asignaciones de créditos adquiridos.
{% endalert %}

## Desglose por regiones de facturación

#### Norteamérica

Estados Unidos, Canadá

#### Resto de África

Angola, Argelia, Benín, Botsuana, Burkina Faso, Burundi, Camerún, Chad, Congo, Eritrea, Costa de Marfil, Etiopía, Gabón, Gambia, Ghana, Guinea-Bissau, Kenia, Lesoto, Liberia y Libia,
Madagascar, Malawi, Mali, Mauritania, Marruecos, Mozambique, Namibia, Níger, Ruanda, Senegal, Sierra Leona, Somalia, Sudán del Sur, Sudán, Suazilandia, Tanzania, Togo, Túnez, Uganda, Zambia.

#### Resto de Asia-Pacífico

Afganistán, Australia, Bangladesh, Camboya, China, Hong Kong, Japón, Laos, Mongolia, Nepal, Nueva Zelanda, Papúa Nueva Guinea, Filipinas, Singapur, Sri Lanka, Taiwán, Tayikistán y Tailandia,
Turkmenistán, Uzbekistán, Vietnam

#### Resto de Europa Central y Oriental

Albania, Armenia, Azerbaiyán, Bielorrusia, Bulgaria, Croacia, República Checa, Georgia, Grecia, Hungría, Letonia, Lituania, Macedonia, Moldavia, Polonia, Rumanía, Serbia, Eslovaquia, Eslovenia, Ucrania.

#### Resto de América Latina

Bolivia, Costa Rica, República Dominicana, Ecuador, El Salvador,
Guatemala, Haití, Honduras, Jamaica, Nicaragua, Panamá, Paraguay, Puerto Rico, Uruguay, Venezuela

#### Resto de Oriente Medio

Bahréin, Irak, Jordania, Kuwait, Líbano, Omán, Qatar, Yemen

#### Resto de Europa Occidental

Austria, Bélgica, Dinamarca, Finlandia, Irlanda, Noruega, Portugal, Suecia, Suiza
