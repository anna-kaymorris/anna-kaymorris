<!DOCTYPE html>
<html>
    <head>
        <title>ID# Lab Test #2</title>
        <style>
        td{
            border: 1px solid green;
            padding: 5px;
            height: 25px;          
        }

        </style>
            
    </head>
    <body>
        <center> 
            Name: Zashaunie Morris (ID#: 2104169)
            <br>

            <form>

           
        <table>
            <col width ="180px">
            <tr><h3>Doe B.M.I. Calculator</h3></tr>
            <tr>
                <td> Height </td>
                <td> <input type="text" size="25px" id="height" min="1" placeholder="enter a number"> </td>
                <td rowspan="2"> <select id="m_inches">
                    <option value="metric">cm / kg</option>
                    <option value="imperial">inches / lbs</option>
                </select></td>
            </tr>
            <tr>
                <td> Weight </td>
                <td> <input type="text" size="25px" id="weight" min="1" placeholder="enter a number"> </td>
            </tr>
            <tr width="45px" id="result">
                <td > <p id="typeOfBMI">= </p> </td>
                <td colspan="2"> 
                    
                    <p id="resTxt">....</p></td>  
            </tr>
            <tr>
                <td colspan="3" align="center">
                    <input type="submit" value="Calculate" id="calcBtn"  style="background-color:blue; color: white;">
                    <input type="submit" value="Cancel" id="cancelBtn" style="background-color: darkorange; color: white;">
                   
                </td>  
            </tr>
            <tr>
                <td colspan="3">
                    You are <input type="text" id="bmiState" size="40px" > </input></>
                </td>
            </tr>
        </table>
    </form>
    </center>
    </body>
</html>


