# table-anf-form
create time table and form using front end
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> School Time Table</title>
    <style>
        table{
            padding:4px;
        }
        tr, td, th {
            border: 2px inset grey;
           
        }
        
        
    </style>
</head>
<body>
    <h2>This is Time Table</h2>
    <table border="4" cellspacing="7" cellpadding="6" bgcolor="#eeeeee">
        <tr>
            <th bo>Days / Periods </th>
            <th>1 </th>
            <th>2 </th>
            <th>3 </th>
            <th> </th>
            <th>4 </th>
            <th>5 </th>
            <th>6 </th>
        </tr>
        <tr>
            <td>Mon</td>
            <td>Science </td>
            <td>English </td>
            <td>Hindi </td>
            <td rowspan="6"  ><div style="writing-mode: vertical-rl; text-orientation: upright;"> BREAK </div></td>
            <td>Maths </td>
            <td>Games </td>
            <td>Moral Science </td>
        </tr>
        <tr>
            <td>Tue</td>
            <td>Science </td>
            <td>English </td>
            <td>Hindi </td>
           
            <td>Maths </td>
            <td>Games </td>
            <td>Moral Science </td>
        </tr>
        <tr>
            <td>Wed</td>
            <td>Science </td>
            <td>English </td>
            <td rowspan="3">Hindi </td>
            
            <td>Maths </td>
            <td>Games </td>
            <td>Moral Science </td>
        </tr>
        <tr>
            <td>thu</td>
            <td>Science </td>
            <td>English </td>
            
            
            <td>Maths </td>
            <td>Games </td>
            <td>Moral Science </td>
        </tr>
        <tr>
            <td>Fri</td>
            <td>Science </td>
            <td>English </td>
            
        
            <td>Maths </td>
            <td>Games </td>
            <td>Moral Science </td>
        </tr>
        <tr>
            <td>Sat</td>
            <td>Science </td>
            <td>English </td>
            <td>Hindi </td>
         
            <td colspan="3">Maths </td>
            
        </tr>
        <tr colspan="8">
            <th colspan="8"  align="center">This is Class VIII</th>
        </tr>

    </table>
</body>
</html>
