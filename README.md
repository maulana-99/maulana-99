<svg width="1000" height="700" viewBox="0 0 1000 700" xmlns="http://www.w3.org/2000/svg" style="background-color:black; font-family: 'OCR A Extended', monospace;">
    <defs>
        <style>
            .title { font-size: 24px; fill: white; font-weight: bold; text-anchor: middle; }
            .heading { font-size: 16px; fill: white; font-weight: bold; }
            .status-text { font-size: 18px; fill: white; font-weight: bold; }
            .status-red { fill: #FF0000; font-weight: bold; }
            .status-green { fill: #00FF00; font-weight: bold; }
            .label { font-size: 12px; fill: white; }
            .data { font-size: 12px; fill: white; }
            .table-header { font-size: 14px; fill: white; font-weight: bold; }
            .table-data { font-size: 12px; fill: white; }
            .box { stroke: white; stroke-width: 3; fill: none; }
            .thin-box { stroke: white; stroke-width: 1; fill: none; }
        </style>
    </defs>

    <rect x="0" y="0" width="1000" height="40" style="fill:none; stroke:white; stroke-width:3;"/>
    <text x="500" y="27" class="title">EMERGENCY RESCUE MANIFEST</text>

    <rect x="20" y="60" width="300" height="150" class="box"/>
    <rect x="25" y="65" width="120" height="25" class="thin-box"/>
    <text x="35" y="83" class="heading">STATUS PANEL</text>
    <rect x="30" y="100" width="280" height="35" class="thin-box"/>
    <text x="40" y="125" class="status-text status-red">SATELLITE UPLINK LOST</text>
    
    <rect x="340" y="60" width="640" height="150" class="box"/>
    <rect x="345" y="65" width="200" height="25" class="thin-box"/>
    <text x="355" y="83" class="heading">DIAGNOSTIC ROUTINE</text>
    <rect x="350" y="100" width="300" height="35" class="thin-box"/>
    <text x="360" y="125" class="status-text status-green">SYSTEM CHECK: [OK]</text>
    <rect x="610" y="105" width="20" height="20" class="thin-box"/>
    <polyline points="613,115 618,125 627,105" style="fill:none; stroke:#00FF00; stroke-width:2;"/>

    <rect x="20" y="230" width="300" height="210" class="box"/>
    <text x="35" y="248" class="heading">CREW MANIFEST</text>
    
    <rect x="30" y="270" width="80" height="80" class="box"/>
    <text x="50" y="315" class="status-text">PHOTO</text>
    <text x="30" y="370" class="label">IDENT: J.DOE/7834</text>
    
    <rect x="120" y="270" width="80" height="80" class="box"/>
    <text x="140" y="315" class="status-text">PHOTO</text>
    <text x="120" y="370" class="label">IDENT: A.LEE/6198</text>
    
    <rect x="210" y="270" width="80" height="80" class="box"/>
    <text x="230" y="315" class="status-text">PHOTO</text>
    <text x="210" y="370" class="label">IDENT: R.KIM/2901</text>
    
    <rect x="20" y="460" width="300" height="150" class="box"/>
    <text x="35" y="478" class="heading">MESSAGE PICKUP</text>
    <rect x="30" y="495" width="280" height="20" class="thin-box"/>
    <text x="40" y="510" class="label">MESSAGE PICKUP</text>
    <text x="40" y="535" class="data">> LOG START: 2024.10.27-14:35Z</text>
    <text x="40" y="555" class="data">> ENCRYPTED MESSAGE INCOMING...</text>
    <text x="40" y="575" class="data">  AWAITING DECRYPTION KEY...</text>
    <text x="40" y="595" class="data">> STATUS: QUEUED</text>


    <rect x="340" y="230" width="640" height="130" class="box"/>
    <text x="355" y="248" class="heading">DATA PURGE METER</text>
    <text x="355" y="270" class="label">DATA PURGERS</text>
    <rect x="350" y="290" width="620" height="30" class="thin-box"/>
    <rect x="350" y="290" width="434" height="30" style="fill:#00FF00;"/> 
    <text x="790" y="310" class="status-text" style="font-size:14px; fill:black;">PURGE 70.00%</text>

    <rect x="340" y="380" width="640" height="230" class="box"/>
    <text x="355" y="398" class="heading">SYSTEM OPERATIONS</text>
    
    <line x1="350" y1="420" x2="970" y2="420" style="stroke:white; stroke-width:1;"/>
    <line x1="700" y1="400" x2="700" y2="600" style="stroke:white; stroke-width:1;"/>

    <text x="360" y="415" class="table-header">CORE FUNCTIONS</text>
    <text x="750" y="415" class="table-header">STATUS</text>

    <text x="360" y="440" class="table-data">CORE FUNCTIONS</text>
    <text x="750" y="440" class="table-data" style="fill:#00FF00;">ONLINE</text>
    <text x="360" y="465" class="table-data">PRIMARY PROCESSOR</text>
    <text x="750" y="465" class="table-data" style="fill:#00FF00;">ONLINE</text>
    <text x="360" y="490" class="table-data">LIFE SUPPORT</text>
    <text x="750" y="490" class="table-data" style="fill:#00FF00;">NOMINAL</text>
    <text x="360" y="515" class="table-data">FUEL INTEGRITY</text>
    <text x="750" y="515" class="table-data" style="fill:#00FF00;">NOMINAL</text>
    <text x="360" y="540" class="table-data">COMM ARRAY</text>
    <text x="750" y="540" class="table-data status-red">OFFLINE</text>
    <text x="360" y="565" class="table-data">BACKUP POWER</text>
    <text x="750" y="565" class="table-data status-red">OFFLINE</text>

    <rect x="20" y="630" width="960" height="50" class="box"/>
    <text x="30" y="655" class="data">DATA BLOCK: [7000]</text>
    
    <g transform="translate(500, 650)">
        <rect x="-150" y="-10" width="300" height="30" fill="white"/>
        <rect x="-140" y="-8" width="5" height="26" fill="black"/>
        <rect x="-130" y="-8" width="2" height="26" fill="black"/>
        <rect x="-125" y="-8" width="8" height="26" fill="black"/>
        <rect x="-110" y="-8" width="1" height="26" fill="black"/>
        <rect x="-105" y="-8" width="5" height="26" fill="black"/>
        <rect x="-95" y="-8" width="10" height="26" fill="black"/>
        <rect x="-80" y="-8" width="4" height="26" fill="black"/>
        <rect x="-70" y="-8" width="6" height="26" fill="black"/>
        <rect x="-60" y="-8" width="1" height="26" fill="black"/>
        <rect x="-50" y="-8" width="8" height="26" fill="black"/>
        <rect x="-35" y="-8" width="2" height="26" fill="black"/>
        <rect x="-25" y="-8" width="5" height="26" fill="black"/>
        <rect x="-10" y="-8" width="10" height="26" fill="black"/>
        <rect x="5" y="-8" width="1" height="26" fill="black"/>
        <rect x="15" y="-8" width="6" height="26" fill="black"/>
        <rect x="30" y="-8" width="3" height="26" fill="black"/>
        <rect x="40" y="-8" width="5" height="26" fill="black"/>
        <rect x="55" y="-8" width="8" height="26" fill="black"/>
        <rect x="70" y="-8" width="2" height="26" fill="black"/>
        <rect x="80" y="-8" width="7" height="26" fill="black"/>
        <rect x="95" y="-8" width="10" height="26" fill="black"/>
        <rect x="110" y="-8" width="5" height="26" fill="black"/>
        <rect x="125" y="-8" width="2" height="26" fill="black"/>
        <rect x="135" y="-8" width="8" height="26" fill="black"/>
        <text x="-120" y="45" class="label" style="font-size:14px; fill:white; text-anchor: middle;">03838</text>
        <text x="110" y="45" class="label" style="font-size:14px; fill:white; text-anchor: middle;">9919</text>
    </g>

</svg>
