$(document).ready(function(){
  $("#a").click(function(){
    var inputVal = $("#tArea").val();

    if (inputVal.toLowerCase().includes("vegan")) {
        alert("Cheescakes contain Dairy");
    }
    else{
        // hide everything
        $(".one").hide();
        $(".two").hide();
        $("#b").hide();
        $("#tArea").hide();
        $("#a").hide();

        var Quantity = $('#Quantity option:selected').text();
        var flavor = $('input[name="topping"]:checked').val();

        // alert(Quantity + " " + flavor); used to see if i got the values 
        $(".p1").text("Order Details")
        $(".ps").text("Thank You!");
        $(".q").text("Your Order Has Been Placed!");
        $(".w").text("Quantity: " + Quantity); 
        $(".e").text("Flavor: " + flavor);
        $(".r").text("Notes: "+ inputVal);

        // everything here is working, tested by making if statement always false 
        
        $(".dropdown-content").click(function(){
            alert("You entered p1!");
        })
    }

  });
});