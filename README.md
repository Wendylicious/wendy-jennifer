# wendy-jennifer
<!DOCTYPE html>
<html>
    <head>
        <style>
            .table { background-color: blue;}
            table{margin-left:auto; margin-right:auto;}
            table, tr, td { border: 1px solid rgb(0, 0, 0); border-collapse: collapse;}
        </style>
    </head>
    <body>

        <ol start="10 ">
            <li>Number one</li>
            <li>Number two</li>
            <li>Number three</li>
            <li>Number four</li>
        </ol>

        <ol type="A">
            <li>Number one</li>
            <li>Number two</li>
            <li>Number three</li>
            <li>Number four</li>
        </ol>


        <ol type="I">
            <li>Number one</li>
            <li>Number two</li>
            <li>Number three</li>
            <li>Number four</li>
        </ol>

        <ol type="a">
            <li>Number one</li>
            <li>Number two</li>
            <li>Number three</li>
            <li>Number four</li>
        </ol>

        <ol type="i">
            <li><a href="https://google.com/"target="_blank">Number one</a></li>
            <li>Number two</li>
            <li>Number three</li>
            <li>Number four</li>
        </ol>

        <h2>Unordered list</h2>
        <ul>
            <ul start="1">
                <li>Number one</li>
                <li>Number two</li>
                <li>Number three</li>
                <li>Number four</li>
            </ul>
    
            <ul style="list-style: circle;">
                <li>Number one</li>
                <ol type="A">
                    <li>Number one</li>
                    <li>Number two</li>
                    <li>Number three</li>
                    <li>Number four</li>
                </ol>
                <li>Number two</li>
                <li>Number three</li>
                <li>Number four</li>
            </ul>

            <dl>
                <dt>Mathematics</dt>
                <dd>Algebra</dd>
                <dd>Real Analysis</dd>
                <dd>ODe</dd>
                <dt>English</dt>
                <dd>Noun</dd>
                <dd>Pronoun</dd>
                <dd>verb</dd>
            </dl>

            <form>
                First Name: <input type="text" name="First name" value="First Name"><br>
                Last Name: <input type="text" name="Last name"><br>
                <input type="radio" name="Male"> Male<br>
                <input type="radio" name="Female"> Female<br>
                Date of birth: <input type="date" name="Date of birth"><br>
                Phone Number: <input type="number" name="Phone number"><br>
                Email: <input type="text" name="Email"><br>
                Favorite food: <input type="text" name="Favorite food"><br>
                Favorite color: <input type="color" name="Favorite color"><br>
                <textarea name="about you" rows="5" cols="10">about you</textarea>
                <select name="states">
                    <option name="abia">Abia</option>
                    <option name="Lagos">Lagos</option>
                </select>

                <table>
                    <tr>
                        <th colspan="3">April scheduele</th>
                    </tr>
                    <tr>
                        <th>Date</th>
                        <th>Departure time</th>
                        <th>Venue</th>
                    </tr>

                    <tr>
                        <td>Mon 4th</td>
                        <td>9:00am</td>
                        <td>Lekki conversation</td>
                    </tr>

                    <tr>
                        <td>Fri-sat 8th-9th</td>
                        <td>3:00pm</td>
                        <td rowspan="2">Agodi parks</td>
                    </tr>

                    <tr>
                        <td>sat-sun</td>
                        <td>2:00pm</td>

                    </tr>

                    <tr>
                        <td>wed 13th</td>
                        <th colspan="2" rowspan="2">Ibadan tour</th>
                        

                    </tr>

                    <tr>
                        <td>Fri 15th</td>
                    </tr>
                </table>
                <input type="submit" value="submit"><br>
            </form>
    
    
            
       
        </ul>
        
    </body>
</html>
