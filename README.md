<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Table</title>
        <title>Time Table</title>
        <style>
            table {
                border-collapse: collapse;
            }    
    
            th,
            td {
                border: 1px solid #dee2e6;
                padding: 10px;
                text-align: center;
            }
    
            th {
                background-color: #f2f2f2;
                color: #343a40;
            }
    
            .highlight {
                background-color: #f8f9fa;
            }
    
            .special {
                background-color: #f0f0f0;
            }
        </style>
    </head>
    
    <body>
        <h1><center><b>TIME TABLE</b></center></h1>
        <!-- <h1><center>hello</center></h1> -->
        <table>
            <tr>
                <th>Day/Period</th>
                <th>I<br>09:00-09:55</th>
                <th>II<br>09:55-10:50</th>
                <th>III<br>10:50-11:00</th>
                <th>11:10-12:05</th>
                <th>IV<br>12:05-01:00</th>
                <th>V<br>01:00-01:50</th>
                <th>VI<br>01:50-02:45</th>
                <th>VII<br>02:45-02:55</th>
                <th>VII<br>02:55-03:50</th>
                
            </tr>
            <tr>
                <td class="highlight"><b>Monday</b></td>
                <td>DTCS603<BR>SU</td>
                <td>DTCS606<BR>RK</td>
                <td rowspan="6" class="special"><b>B<BR>R<BR>E<BR>A<BR>K</b></td>
                <td colspan="2">LAB</td>
                <td rowspan="5" class="special"><b>L<BR>U<BR>N<BR>C<BR>H</b></td>
                <td colspan="3">PLACEMENT CLASS</td>
                
            </tr>
            <tr>
                <td class="highlight"><b>Tuesday</b></td>
                <td colspan="2" >LAB</td>
                <TD colspan="2" 9>DIPCS604<BR>HP</TD>
                <TD COLSPAN="2" >DTCS606<BR>RK</TD>
                <td>SPORTS</td>
            </tr>
            <tr>
                <td class="highlight"><b>Wednesday</b></td>
                <td>DTCS601<BR>DT</td>
                <td></td>
                <td>DTCS606<BR>RK</td>
                <td>DTCS602<BR>HP</td>
                <td colspan="3">DTCS602<BR>HP</td>
            </tr>
            <tr>
                <td class="highlight"><b>Thursday</b></td>
                <td>DTCS602<BR>HP</td>
                <td>DTCS603<BR>SU</td>
                <td>DTCS606<BR>RK</td>
                <td>DTCS601<BR>DT</td>
                <td colspan="2" >DSCS601<BR>SJ</td>
                
            </tr>
            <tr>
                <td class="highlight"><b>Friday</b></td>
                <td>DTCS606<BR>RK</td>
                <td>DTCS601<BR>DT</td>
                <td>DTCS603<BR>SU</td>
                <td>DTCS602<BR>HP</td>
                    <td colspan="3" >MOOCS SEMINAR</td>
            </tr>
        </table>
    </body>
    
    </html>
