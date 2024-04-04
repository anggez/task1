<!DOCTYPE html>
<html>
    
    <style>
        body{
            background-position: center;
            background-repeat: no-repeat;
            height: 600px;
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            position: relative;
            text-align: center;
            background-image: url(https://previews.123rf.com/images/matttilda/matttilda1209/matttilda120900020/15417704-vintage-photography-background.jpg);
            
            
        }
        h2{
            text-align: center;
            text-decoration-style: double;
            text-shadow: 2px 2px rgb(217, 98, 29);
            font-size: 40px;
            font-family: 'lucida handwriting', cursive;
            
            
        }
        p{
            text-align: center;
            font-size: 30px;
            border: solid;
            border-color: rgb(173, 148, 23);
            border-style: double;
        }

    </style>
<body>
   
    <h2>What Can JavaScript Do?</h2>

    <p>JavaScript can change HTML attribute values.</p>
    
    <p>The main function of the eyes is enabling people to see. All the parts of the eye work together to allow vision. They take in light from the environment and send visual information for the brain to process.</p>
    
    <button onclick="document.getElementById('myImage').src='haha.png'">close eyes</button>
    
    <img id="myImage" src="haha.png" style="width:200px">
    
    <button onclick="document.getElementById('myImage').src='huhu.png'">open eyes</button>
    


</body>
</html>
