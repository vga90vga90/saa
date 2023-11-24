var por = document.getElementById("Portugal");
var en = document.getElementById("english");
por.onclick = function () {
  var home = document.getElementById("home");
  // newHome = home.replace(home, "Casa");
  home.innerHTML = "Casa";
};

$(document).ready(function () {
  $(window).scroll(function () {
    if ($(this).scrollTop() > 400) {
      $(".scroll-top").fadeIn(300);
    } else {
      $(".scroll-top").fadeOut(300);
    }
  });

  // $("a").click(function () {
  //   // e.preventDefault();
  //   $("html,body").animate(
  //     {
  //       scrollTop: $("#" + $(this).data("scroll")).offset().top,
  //     },
  //     1000
  //   );
  // });

  // $(window).scroll(function () {
  //   if ($(this).scrollTop() <
  //     $(".nav").css({ position: "relative", top: "100px" });
  //     // $(".bdy").css({
  //     //   top: "120px",
  //     //   transition: "1s",
  //     //   position: "relative",
  //     // });
  //   } else {
  //     $(".nav").css({ position: "fixed", top: "0px" });
  //     // $(".bdy").css({ top: "210px", position: "relative", transition: "1s" });
  //   }
  // });

  $(window).scroll(function () {
    if ($(this).scrollTop() > 280) {
      $(".nav").css({ position: "fixed", top: "0px", display: "block" });
      $(".navs").css({ position: "relative", visibility: "hidden" });
      $(".bdy").css({ top: "100px" });
    } else {
      $(".navs").css({ visibility: "visible", top: "100px" });
      $(".nav").css({ display: "none" });
      $(".bdy").css({ top: "100px" });
      // $(".nav").slideDown();

      // $(".navs").css({ position: "absolute", top: "100px", display: "block" });

      // $(".navs").slideDown();
    }
  });

  $(".download").click(function () {
    $(".dow-link").toggle(100);
  });

  // $(window).scroll(function () {
  //   if ($(this).scrollTop()) {
  //     $(".nav");
  //   }
  // });

  $(".scroll-top").click(function () {
    $("body ,html").animate({
      scrollTop: 0,
    });
  });
  $(".rel,.drop").mouseenter(function () {
    $(".drop").slideDown();
  });
  $(".drop").mouseleave(function () {
    $(".drop").slideUp(100);
  });
  // $("#fa-menu").click(function () {
  //   $("#fa-exit").slideDown();
  //   $("#fa-menu").css({ display: "none" });
  // });
  // $("#fa-exit").click(function () {
  //   $("#fa-exit").css({ display: "none" });
  //   $("#fa-menu").slideDown();
  // });
});
