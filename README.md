- 👋 Hi, I’m @ShaikNazeer0073

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fitness & Sports</title>
    <link href="style.css" rel="styesheet">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: black;
            position: relative;
            background-image: url(https://i.pinimg.com/736x/51/da/cb/51dacb2372800ed4788d46c8c19ea5ff.jpg);
        }

        header {
            background-color: black;
            color: #fff;
            padding: 10px;
            text-align: center;
        }
        nav {
           background-color: rgba(215, 26, 26, 0.637);
            padding: 12px;
            text-align: center;


        }

        nav a {
            position: relative;
            text-decoration: none;
            padding: 10px 10px 10px 10px;
            margin: 10px 10px 10px 10px;
            color: rgb(255, 255, 255);
            font-weight: 500;
            box-shadow:rgba(166, 30, 30, 0.882)
        }

        nav a::after {
            content: '';
            position: absolute;
            bottom: -2px;
            left: 0;
            width: 0;
            height: 2px;
            background-color: white;
            transition: width 0.3s ease;
        }

        nav a:hover::after {
            width: 100%;
        }

        section {
            padding: 100px;
        }

        article {
            margin-bottom: 20px;
            padding: 10px;
            background-color: #fff;
            border-radius: 5px;
        }

        h2 {
            color: #333;
        }

        footer {
            background-color: maroon;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
     </style>
     <style>
        /* CSS for the dropdown menu */
        .dropdown {
            position: relative;
            display: inline-block;
            color: red;
        }

        .dropdown-content{
            display: none;
            position: absolute;
            background-color: rgb(255, 255, 255);
            min-width: 5px;
            box-shadow: 0px 8px 16px 0px rgba(11, 11, 11, 0.882);
            z-index: 1;
        }
        .dropdown:hover .dropdown-content {
   display: block;
}
        .dropdown-content a {
            color: rgb(0, 0, 0);
            text-decoration: none;
            display: block;
        }

        .dropdown-content a:hover {
           background-color: rgb(241, 151, 232);
            display: block;
        }
    </style>
    <style>
        .dini{
            float: right;
            color: black;
            font-weight:400;
            font-style: italic;
        }
    </style>
 <style>
    /* Your CSS styles */
    /* ... */
    .container {
        position: relative;
        width: 300px; /* Adjust width as needed */
    }

    .container img {
        width: 100%;
        height: auto;
        display: block;
    }

    .overlay {
            position: absolute;
            top: 0;
            left: 0;
            bottom: 0;
            right: 0;
            background-color: rgba(0, 0, 0, 0.5); /* Semi-transparent black overlay */
            color: white;
            font-size: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            opacity: 0;
            transition: opacity 0.3s;
        }


    .container:hover .overlay {
        opacity: 1;
    }
</style>
<style>
    .link{
        display: inline-block;
            padding: 10px 20px;
            text-decoration: none;
            background-color: #007bff;
            color: white;
            border-radius: 5px;
            transition: background-color 0.3s;
    }
</style>
<style>
    .dropbtn{
        background-color: #0000; /* Fallback color */
  background-image: linear-gradient(to bottom, #e224e6, #060505); /* Gradient */
  color: white;
  padding: 10px 12px 10px 10px;
  margin: 5px;
  border: none;
  border-radius: 10px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  transition-duration: 0.4s;
  cursor: pointer;
}

.dropbtn:hover {
  background-image: linear-gradient(to bottom, #c925cf, #f8f8f7); 
  color: black;/* Gradient on hover */
}
    
</style>
</style>
</head>
<body>
       
           </script>

    <header>
        <h1>Fitness & Sports</h1>
    </header>
 </script>
        </div>
    <nav>
   
        <div class="dropdown">
            <button class="dropbtn" onclick="toggleDropdown(1)">Cricket</button>
            <div class="dropdown-content">
                <a href="">IPL</a>
                <a href="">ICC</a>
                <a href="">T20</a>
                <a href="">ODI</a>
                <a href="">Test WC</a>
            </div>
                <!-- Add more league options as needed -->
            </div>
            <div class="dropdown">
                <button class="dropbtn" onclick="toggleDropdown(2)">Football</button>
                <div class="dropdown-content">
                    <a href="">EPL</a>
                    <a href="">La Liga</a>
                    <a href="">Bundesliga</a>
                    <a href="">League 1</a>
                    <a href="">ISL</a>
                </div>
                </div>
                    <!-- Add more league options as needed -->
                </div></li>
                <div class="dropdown" onclick="toggleDropdown(3)">
                    <button class="dropbtn">Basketball</button>
                    <div class="dropdown-content" id="dropdown-3">
                        <a href="">NBA</a>
                        <a href="">Lakers</a>
                        <a href="">BSL</a>
                        <a href="">Spain Liga</a>
                        
                        <a href="https://australia.rugby/participate/rugby-administration/registration">EuroLeague</a>
                    </div>
                        <!-- Add more league options as needed -->
                    </div>
                </div>
                <div class="dropdown" onclick="toggleDropdown(4)">
                    <button class="dropbtn">Running</button>
                    <div class="dropdown-content" id="dropdown-4">
                        <a href="">jogging</a>
                        <a href="">Short run</a>
                        <a href="">Sprint</a>
                        <a href="">Long run</a>
                        
                        <a href="https://australia.rugby/participate/rugby-administration/registration">League-R</a>
                    </div>
                    </div>
                    <div class="dropdown" onclick="toggleDropdown(5)">
                        <button class="dropbtn" id="dropdown-5">Yoga</button>
                        <div class="dropdown-content">
                            <a href="">Ashtanga yoga</a>
                            <a href="">Hot yoga</a>
                            <a href="">Power</a>
                            <a href="">vinyasa yoga</a>
                            <a href="">TAL</a>
                        </div>
            
    </nav>
    <section>
        <article>
            <h2>SPORTS</h2>
            <h2><b>What does term 'Sport' mean ?</b></h2>
            <p>The term <b>'Sport'</b> refers to a physical activity or game that involves skill, physical exertion, and competition. It's a broad concept that encompasses various activities where individuals or teams engage in organized play according to specific rules or regulations.</p>
            <div class="container">
            <img src="https://imgs.search.brave.com/iWBBOvJrDIii0mHxr7ktNXcz4czhdNL9ar4Xw-qNz7c/rs:fit:500:0:0/g:ce/aHR0cHM6Ly9pbWcu/ZnJlZXBpay5jb20v/ZnJlZS1waG90by9z/cG9ydHMtdG9vbHNf/NTM4NzYtMTM4MDc3/LmpwZz9zaXplPTYy/NiZleHQ9anBn" alt="img">
            <div class="overlay">Sports</div>
            </div>
            <pre><b>Sports encompass a wide range of physical activities or games that involve organized participation, skill development, and competition. <br>These activities can be individual or team-based and are often governed by rules and customs.</b></pre>
        </article>

        <article>
            <h2>SKILLS</h2>
            <p><b>Physical Activity:</b>
                Sports involve physical exertion and movement, which can vary widely depending on the specific sport. They often require strength, agility, speed, endurance, coordination, and flexibility.</p>
            <p><b>Skill Development:</b>
                Participation in sports often requires the development and refinement of specific skills. These skills can range from fundamental movements like running, jumping, or throwing to more specialized techniques unique to each sport.</p>
                <div class="container">
                    <img src="https://imgs.search.brave.com/35xfY9hLaztzr_BfLj4Darh5pj9UwhaGpPMvQm5WSfU/rs:fit:860:0:0/g:ce/aHR0cHM6Ly9tZWRp/YS5nZXR0eWltYWdl/cy5jb20vaWQvMTM1/MjUxMjIwMS9waG90/by9jb25jZXB0dWFs/LW1vZGVybi1waG90/by13aXRoLXNwb3J0/cy1lcXVpcG1lbnQu/anBnP3M9NjEyeDYx/MiZ3PTAmaz0yMCZj/PUc5aXJfRjU1anpj/ZDVfRHd0eXhaVEo3/ZXFiRkNvLVZsd0hx/clRvbFhhUUk9" alt="img" height="700" width="700"><br>
                    <div class="overlay">SKILLS</div>
                    </div>

            
            <h1>Sports exist at various levels, from amateur to professional. Amateur sports are often played for recreation, fitness, or personal enjoyment, while professional sports involve athletes who compete at the highest levels for rewards, recognition, and sometimes financial gain.

                Overall, sports encompass a diverse range of activities that promote physical, mental, and social well-being while fostering competition, camaraderie, and a sense of achievement among participants.</h1>
        </article>

        <article>
            <h2>Sports & Leagues</h2>
            <h1>Sports leagues are organized structures that oversee and manage competitions among teams or individuals within a specific sport. These leagues create a framework for regular competition, determine rules and regulations, and often establish a hierarchy of competitions or tournaments.
            </h1><br>
            <div class="container">
                <img src="https://imgs.search.brave.com/jxlILhYh3nwD7jQHL2pMjptjexiPK8r_hUNM3xmTfqs/rs:fit:860:0:0/g:ce/aHR0cHM6Ly9zdGF0/aWMuc3RhcnR1cHRh/bGt5LmNvbS8yMDIz/LzExL1RvcC0xMC1S/aWNoZXN0LVNwb3J0/cy1MZWFndWUtU3Rh/cnR1cHRhbGt5Lmpw/Zw" alt="img" width="700" height="700">
                <div class="overlay">Sports and leagues</div>
                </div>
               <hr> <b>Structured Competition:</b> They provide a structured environment for competition, often involving a schedule of matches or games throughout a season.
                
               <hr> <b>Regulations and Rules:</b> Leagues establish rules and regulations governing player conduct, gameplay, scheduling, and other aspects to ensure fair play and maintain consistency across all participants.</p>
          
        </article>

        <article>
            <h2></h2>
            <div class="container">
                <img src="https://imgs.search.brave.com/LontooHx0YF1oGmWy2yv6FywRAmPWdoXMU7Xb7dslJ0/rs:fit:860:0:0/g:ce/aHR0cHM6Ly93d3cu/a3JlZWRvbi5jb20v/d3AtY29udGVudC91/cGxvYWRzLzIwMjIv/MDcvTW9zdC1XYXRj/aGVkLVNwb3J0cy1M/ZWFndWVzLTEtNjk2/eDQxOC5qcGc" alt="img" width="700" height="700" >
                <div class="overlay">Leagues</div>
                </div>
            <p><b>Standings and Rankings:</b> Leagues maintain standings or rankings based on wins, losses, points, or other criteria, determining the positions of teams or individuals within the league.

             <hr>   <b>Playoffsand Championships: </b> Many leagues have postseason playoffs or championship events where top-performing teams or individuals compete for the ultimate title or trophy.
                
              <hr>  <b>Promotion and Relegation (in some leagues):</b> In certain leagues, teams may be promoted to higher divisions or relegated to lower divisions based on their performance in a given season.</p>
        </article>

        <article>
            <h2>Fitness</h2>
            <p>Fitness encompasses a range of physical activities and behaviors aimed at improving or maintaining health and overall well-being. It involves various components such as cardiovascular endurance, muscular strength, flexibility, and body composition. Here are some key aspects to consider when it comes to fitness:</p>
            <div class="container">
                <img src="https://imgs.search.brave.com/jB_kiPQUsvktntSQXWuUXX3-eykCjmNmUdE1ZmrL-qA/rs:fit:860:0:0/g:ce/aHR0cHM6Ly9tZWRp/YS5nZXR0eWltYWdl/cy5jb20vaWQvMTA4/NDI1MTA4NC9waG90/by9wZXJzb25hbC13/ZWlnaHQtdHJhaW5p/bmctaW4tdGhlLWd5/bS5qcGc_cz02MTJ4/NjEyJnc9MCZrPTIw/JmM9YUd1bkdLSHdw/YTRMVXBPb3FjQlR1/aER6Mk1GcGZQUzB2/QUo2ak1PRjlfdz0" alt="img" width="700" height="700">
                <div class="overlay">Fitness</div>
                </div>

               <h1> Importance of Fitness:</h1>
<p><br><b>Exercise:</b>Regular physical activity is fundamental to fitness. This can include aerobic exercises like running, swimming, or cycling, which improve cardiovascular health, as well as strength training exercises like weightlifting or bodyweight exercises, which enhance muscular strength and endurance.</p>


<p><b>Nutrition: </b>A balanced diet is essential for supporting fitness goals. This involves consuming a variety of nutrient-dense foods including fruits, vegetables, lean proteins, whole grains, and healthy fats. Proper nutrition provides the energy needed for workouts, supports muscle recovery, and helps maintain overall health.</p>


<p><b>Rest and Recovery:</b>Adequate rest is crucial for allowing the body to recover and adapt to exercise. This includes getting enough sleep each night, as well as incorporating rest days into your workout routine to prevent overtraining and reduce the risk of injury.</p>
<p><b>Consistency:</b>Consistent effort over time is key to achieving and maintaining fitness goals. This involves establishing a regular exercise routine and making healthy lifestyle choices consistently over the long term.</p>
<p><b>Goal Setting:</b> Setting specific, measurable, achievable, relevant, and time-bound (SMART) goals can help you stay focused and motivated. Whether your goal is to lose weight, build muscle, improve endurance, or enhance overall health, having a clear plan in place can increase your chances of success.</p>
<p><b>Mind-body connection:</b>  Physical fitness is not only about the body but also about the mind. Practicing mindfulness techniques such as meditation, yoga, or deep breathing exercises can help reduce stress, improve mental focus, and enhance overall well-being, complementing your physical fitness efforts.</p>
        </article>
<article>
<h2>Some of the major importance of fitness:</h2>
<div class="container">
    <img src="https://imgs.search.brave.com/ou_DGK1oa4xig_l62nnfsF9SckLM9wAulgXKBfuUE5c/rs:fit:860:0:0/g:ce/aHR0cHM6Ly9tZWRp/YS5pc3RvY2twaG90/by5jb20vaWQvNTEy/ODg5MTg3L3Bob3Rv/L2dldHRpbmctdGhl/LWp1bXAtb24tZ29v/ZC1oZWFsdGguanBn/P3M9NjEyeDYxMiZ3/PTAmaz0yMCZjPWNO/SFZ1R2M4TG93UzBx/VWR0RFI4WVd5X3Bs/ZjdkZVBYTzRmdEFy/a0Rnd0U9" alt="image" width="700" height="700">
    <div class="overlay">Fitness = Health</div>
    </div>
<p><b>Physical Health:</b>  Regular exercise and fitness activities contribute to better physical health by improving cardiovascular health, reducing the risk of chronic diseases such as heart disease, diabetes, and obesity, enhancing immune function, and promoting longevity.</p>
<p><b>Mental Health:</b> Exercise has been shown to have numerous benefits for mental health, including reducing symptoms of depression and anxiety, improving mood and self-esteem, reducing stress, and enhancing cognitive function and overall mental well-being.</p>
<p><b>Increased Energy Levels:</b> Regular exercise boosts energy levels and reduces fatigue by improving circulation, increasing oxygen supply to cells, and enhancing overall physical endurance and stamina.</p>
<p><b>Weight Management:</b> Fitness plays a crucial role in weight management by burning calories, increasing metabolism, and building lean muscle mass. Maintaining a healthy weight reduces the risk of obesity-related health problems and enhances overall well-being.</p>
<p><b>Prevention of Injuries:</b> A strong and flexible body is less prone to injuries, both during physical activities and in daily life. Fitness training helps improve balance, coordination, and flexibility, reducing the risk of falls and accidents.</p>
<p><b>Productivity and Performance:</b>Physical fitness has been linked to improved productivity, concentration, and cognitive function, leading to better performance in academic, professional, and personal endeavors.</p>
</article>
        <!-- Add more articles as needed -->
       <article>
        <form>
            <h4>Any Queries?</h4>
            <input type="email" id="email" placeholder="Email">
            <textarea id="message" placeholder="Message"></textarea>
            <button type="submit">Submit</button>
            <h2>You can Register from our Regisration form given below</h2>
            <a href="file:///C:/Users/HP/Downloads/HTML/ai.html" class="link">Register Now!!</a>
        </form>
       </article>
         <!-- Your HTML content -->
         <button onclick="showAlert()" class="dini">The End</button>

         <!-- Your remaining HTML content -->
     
         <script>
             // JavaScript for showing alert
             function showAlert() {
                 alert("Thanks for visiting our website :)");
             }
         </script>
    </section>
    
    <footer>
        &copy; 2024 Fitness & Sports Platform
    </footer>

</body>
</html>
<!---
ShaikNazeer0073/ShaikNazeer0073 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
