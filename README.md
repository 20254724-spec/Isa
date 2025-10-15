
    <style>
        #content{
            background-color:lightpink;
            margin: auto;
            width: 1190px;
            font-family: sans-serif;
        }
       #bio{
            font-family: sans-serif;
            float:right;
            
            
        }

    </style>
</head>
<body>
<form>
    <div id="content">
        <fieldset>
            <legend>Personal Detsils</legend>
    <br>
    Fullname <br><input type="text"><br>
    Email <br><input type="text"><br>
    Password <br><input type="password"><br>
    Age <br><input type="number">
        </fieldset>
    </form>
    <form >
        <fieldset>
            <legend>Preferences</legend>
    <br>
    Gender <br><input type=radio name="Gender">Male<br>
    <input type=radio name="Gender">Female<br>
    <input type=radio name="Gender">Other<br>
    Interests <br><input type="checkbox">Web Development<br>
    <input type="checkbox">Design<br>
    <input type="checkbox">AI/ML<br>
    Country <br>
    <select>
        <option value="Country">Philippines</option>
        <option value="Country">Spain</option>
        <option value="Country"> Canada</option>
        <option value="Country"> United States</option>
        <option value="Country"> south korea</option>
    </select><br>
   <div id="text">Short bio <br><input type="textarea"width="500px"></div>
   
   <div id="bio"><button>Reset</button>
    <button>Submmit</button></div>

    
    </form>
    
    
    </div>
    
</body>
</html>
