# TABLE-USING-HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
    <h1><center>Time Table</center></h1>

    <table border = "3" width = "100%" cellpading = "10">
        <thead>
            <!-- tr>th{Headin-$}*5 -->
            <tr>
                <th>Day/Period</th>
                <th>9:30 - 10:20</th>
                <th>10:20 - 11:10</th>
                <th>11:10 - 12:00</th>
                <th>12:00 - 12:40</th>
                <th>12:40 - 1:30</th>
                <th>10:30 - 2:20</th>
                <th>2:20 - 3:10</th>
                <th>3:10 - 4:00</th>
            </tr>

        </thead>
        <tbody>
            <tr>
                <tr>
                    <td>Monday</td>
                    <td>Eng</td>
                    <td>Mat</td>
                    <td>Che</td>
                    <tH rowspan="6">LUNCH</th>
                    <td colspan="3"><center>lab</center></td>
                    <td>phy</td>
                </tr>
                <tr>
                    <td>Tuesday</td>
                    <td colspan="3"><center>lab</center></td>
                    <td>Eng</td>
                    <td>Che</td>
                    <td>Mat</td>
                    <td>SPORTS</td>
                </tr>
                <tr>
                    <td>Wednesday</td>
                    <td>Mat</td>
                    <td>Phy</td>
                    <td>Eng</td>
                    <td>Che</td>
                    <td colspan="3"><center>Library</center></td>
                </tr>
                <tr>
                    <td>Thursday</td>
                    <td>Phy</td>
                    <td>Eng</td>
                    <td>Che</td>
                    <td colspan="3"><center>lab</center></td>
                    <td>Mat</td>
                </tr>
                <tr>
                    <td>Friday</td>
                    <td colspan="3"><center>lab</center></td>
                    <td>Mat</td>
                    <td>Che</td>
                    <td>Eng</td>
                    <td>phy</td>
                </tr>
                <tr>
                    <td>Saturday</td>
                    <td>Eng</td>
                    <td>Che</td>
                    <td>Mat</td>
                    <td colspan="3"><center>Seminar</center></td>
                    <td>SPORTS</td>
                </tr>
            </tr>
            
        </tbody>
    </table>
</body>
</html>
