$(document).ready(function(){

    $('.money').mask('00.000.000.000.000,000', {reverse: true});
     // Loading
     users = JSON.parse(localStorage.getItem("users") || "[]");
     // console.log("# of users: " + users.length);
 
     users.forEach(function(user, index) {
     // console.log("[" + index + "]: " + user.id);
     
       $("#result").prepend('<p class="result" id="r_'+user.id+'">You spent <u class=masked> '+user.gold+'</u> <img class="icon" src=images/gold.png>  and <u class=masked>'+user.sky+'</u> <img class="icon" src=images/sky.png>  for <u class=masked>'+user.cov+'</u> <img class="icon" src=images/covenant.png>  and <u class=masked>'+user.mys+'</u> <img class="icon" src=images/mystic.png> on '+user.data+'. <a onclick="deleteR('+index+', '+user.id+');"> <img class="icon" src="images/delete.png"> </a></p><br> ');
       $(".masked").mask('00.000.000.000.000,000', {reverse: true});
   
     });
 
     
     });
 
     //Delete result from storage and array
     function deleteR(indexr, id) {
       if (confirm('Are you sure you want to delete from history?')) {
       users.splice(indexr, 1);
       localStorage.setItem("users", JSON.stringify(users));
       $( "#r_"+id ).remove();
       }
     }
 
     //Function to calculate and save
     function calculate() { 
 
       var isValid;
     $("input").each(function() {
       var element = $(this);
       if (element.val() == "") {
           isValid = false;
       }
     });
 
     if(isValid == false) {
       alert("Blank input!")
       return;
     }
 
     var rgold = $("#sgold").val().replace(/ |,|\.|/g, "") - $("#fgold").val().replace(/ |,|\.|/g, "");
     var rsky = $("#ssky").val().replace(/ |,|\.|/g, "") - $("#fsky").val().replace(/ |,|\.|/g, "");
     var rcov = $("#fcov").val().replace(/ |,|\.|/g, "") - $("#scov").val().replace(/ |,|\.|/g, "");
     var rmys = $("#fmys").val().replace(/ |,|\.|/g, "") - $("#smys").val().replace(/ |,|\.|/g, "");
 
       // Modifying
     var user = {
       id: Math.floor(Math.random() * 1000000),
       gold: rgold,
       sky: rsky,
       cov: rcov,
       mys: rmys,
       data: moment().format('LLL')
     };
 
     
   $("#result").prepend('<p class="result">You spent <u class=masked>'+rgold+'</u> <img class="icon" src=images/gold.png>  and <u class=masked>'+rsky+'</u> <img class="icon" src=images/sky.png>  for <u class=masked>'+rcov+'</u> <img class="icon" src=images/covenant.png>  and <u class=masked>'+rmys+'</u> <img class="icon" src=images/mystic.png> on '+moment().format('LLL')+'.</p><br> ');
 
   // Saving
   users.push(user); 	
   localStorage.setItem("users", JSON.stringify(users));
   
     }

     function clear(e){
      e.preventDefault();
      $('#bform')[0].reset();
      $('#fform')[0].reset();
     }
   
