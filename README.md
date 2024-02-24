# tut
<!DOCTYPE html>
<html>
    <head>
        <title>Submission form</title>
        <style>
            h1{
                font-family:'Courier New', Courier, monospace;
                text-align: center;
                background-color: honeydew;
                font-size: 40px;
                font-weight:290;
            }
            label{
                font-family: 'Courier New', Courier, monospace;
                font-size: 20px;
                font-weight: 500;
                line-height: 60pt;
            }
            #area{
                font-size: small;
            
            }
        
        </style>
    </head>
    <body style="background-color:rgb(228, 202, 202);">
    <h1>Admission form</h1>
    <form>
        <label><strong>Name </strong> :&nbsp;&nbsp;&nbsp;&nbsp;<input type="text" style="color: ghostwhite; border-color: aliceblue;" /></label>
        <br>
        <label><strong>Last Name</strong> :&nbsp;&nbsp;&nbsp;&nbsp;<input type="text" style="background-color: ghostwhite; border-color: aliceblue;"/></label>
        <br>
        <label><strong>Skills</strong> :&NonBreakingSpace;<br><textarea id="area" rows="10" cols="100">Write min 100 characters</textarea></label>
        <br>
        <label><strong>Sex</strong> :</label>&nbsp;&nbsp;&nbsp;&nbsp;
        <input type="radio" name="male" value="Male"><strong>Male</strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="radio" name="female" value="Female"><strong>Female</strong>
        <br>
        <label><strong>Contact</strong> :&nbsp;&nbsp;&nbsp;&nbsp;<input type="text" style="color:ghostwhite ; border-color: aliceblue;" /></label>
        <br>
        <label><strong>Add resume/CV</strong> :&nbsp;&nbsp;&nbsp;&nbsp;<input type="file" id="file" name="jpg" accept=".jpg, .jpeg, .png"/> </label>
        <br>
        <br>
        <div align="center">
        <input type="submit" value="Submit">
        </div>


        
    </form>
    
    </body>
</html>
