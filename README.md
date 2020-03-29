<h1>Be The Hero</h1>
<p>
    Aplicação Back-end feita em NodeJS
</p>

<p>Segue abaixo os endpoints:</p>
<ul>
    <li>Session
        <ul>
            <li>/sessions - POST</li>
            <li>BODY: (id)</li>
        </ul>
    </li>
    <li>Profile
        <ul>
            <li>/profile - GET</li>
            <li>Header: (Authorization)</li>
        </ul>
    </li>
    <li>Ongs
        <ul>
            <li>/profile - POST</li>
            <li>Header: (Authorization)<br/>
                Body: (name, email, whatsapp, city, uf)
            </li>
        </ul>
    </li>
    <li>Incidents
        <ul>
            <li>/incidents - GET</li>
            <br/>
            <li>/incidents/:id - DELETE</li>
            <li>Header: (Authorization)</li>
            <br/>
            <li>/incidents/:id - DELETE</li>
            <li>Header: (Authorization)<br/>
                Body: (title, description, value)
            </li>
        </ul>
    </li>
</ul>
