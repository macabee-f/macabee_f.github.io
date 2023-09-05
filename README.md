


<!doctype html>
<html>

<html lang="en">

<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>(NAME)</title>

</head>
<style>
    body {
        background: rgb(15, 155, 125);
    }

    .welcome {
        text-align: center;
         font-weight: normal;
    }
    .headlines{
     font-weight: normal;
    }

    .subtext {
        text-align: center;
        font-weight: normal;
        
    }

    .tabs {
        text-align: right;
        
    }

    [data-tab-info] {
        display: none;
        
    }

    .active[data-tab-info] {
        display: block;
        
    }

    .tab-content {
        font-size: 20px;
        font-family: Impact;
        font-weight: normal;

    }

    .tabs {
        font-size: 20px;
        color: rgb(255, 255, 255);
        display: ;
        margin: ;

    }

    .tabs span {
        background: rgb(28, 45, 38);
        padding: 10px;
        border: 1px solid rgb(255, 255, 255);
    }

    .tabs span:hover {
        background: rgb(29, 185, 112);
        cursor: pointer;
        color: black;
    }
</style>

<body>
    <div class="tabs">
        <span data-tab-value="#tab_1">Home</span>
        <span data-tab-value="#tab_2">About Me</span>
        <span data-tab-value="#tab_3">Interviews</span>

    </div>

    <div class="tab-content">
        <div class="tabs__tab active" id="tab_1" data-tab-info>
            <p>
            <h1 >Welcome to Mac's Movies</h1>

      

        </div>
        <div class="tabs__tab" id="tab_2" data-tab-info>
        <h1 >About Me</h1>
          <h2 class = "headlines" >Who I Am</h2>
           <h3 class = "subtext" >I'm currently a rising senior at Union County Magnet High School in Scotchplains, NJ</h3>
          
          <p>
</p>
      <h2 class = "headlines">What I do</h2>
            <p class="subtext">I make videos based on interviews I've conducted with local business owners!
            </p>

            <h2 class = "headlines"> How I Want To Help </h2>
            <p class="subtext">I want to show others in my town, Garwood, NJ, that the people around them contribute a lot to daily life</p>

            
            </p>
<h2 class = "headlines" > </h2>
<p>

</p>

<h6 class = "subtext">

</h6>

        </div>
        <div class="tabs__tab" id="tab_3" data-tab-info>
            <h2>Explore Some Of The Interviews I've Held</h2>
            <a href="https://drive.google.com/file/d/1ZPVAAkIYmGVmYXqFl_5qrnhw6H14XgPM/view?usp=drive_link">Interview With Molly(music teacher)</a>

            <script type="text/javascript">
                const tabs = document.querySelectorAll('[data-tab-value]')
                const tabInfos = document.querySelectorAll('[data-tab-info]')

                tabs.forEach(tab => {
                    tab.addEventListener('click', () => {
                        const target = document
                            .querySelector(tab.dataset.tabValue);

                        tabInfos.forEach(tabInfo => {
                            tabInfo.classList.remove('active')
                        })
                        target.classList.add('active');
                    })
                })
                 
                
                
            </script>
             <div class="tabs__tab" id="tab_4" data-tab-info>
             
             
             
             </div>



</body>



</html>






