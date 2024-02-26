<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="shortcut icon" type="image/png" href="favicon.png">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=1000">
    <link href="style.css" rel="stylesheet">
    <title>Zenqi</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.1/jquery.min.js"></script>
</head>
<body>
    <h3 class="title">erudite solari.</h3>
    <div class="container">
        <div class="socials"> 
            <img class="sc github" src="github.png">
            
            <img class="sc facebook" src="facebook.png">
        </div>
        <h3 class="motto">Motto</h3>
        <h3 class="motto-dc">“Intelligence is the ability to adapt to change.”</h3>
        
        <div class="cnd">
            <div class="bx gh">
                <h3 class="gh-txt">@ohitszenqi</h3>
                <h3 class="gh-ds">github</h3>
            </div>
            <div class="bx fb">
                <h3 class="fb-txt">@Sean</h3>
                <h3 class="fb-ds">facebook</h3>
            </div>
        </div>
        <div class="projects">
            <h3 class="ttl">Projects</h3>
            <div class="rblx-cn">
                <h3 class="rblx-ttl">VoidBlox</h3>
                <h3 class="rblx-desc">A Roblox information fetcher Discord bot that can fetch "Users, Places, and Avatars"</h3>
                <img class="rblx-img" src="rblx.jpg">
            </div>

            <div class="game-cn">
                <h3 class="rblx-ttl">Filipino Nextbots</h3>
                <h3 class="rblx-desc">A roblox game inspired by Garry's Mod but with a filipino nextbots</h3>
                <img class="rblx-img" id="hehe" src="./pictures/0.png">
                <img class="arrow-0" src="arrow0.png">
                <img class="arrow-1" src="arrow1.png">
            </div>

            <h3 class="chrm">ddsdsd</h3>

            
        </div>
    </div>
    <script>
        var isMobile = false
        
        if(/(android|bb\d+|meego).+mobile|avantgo|bada\/|blackberry|blazer|compal|elaine|fennec|hiptop|iemobile|ip(hone|od)|ipad|iris|kindle|Android|Silk|lge |maemo|midp|mmp|netfront|opera m(ob|in)i|palm( os)?|phone|p(ixi|re)\/|plucker|pocket|psp|series(4|6)0|symbian|treo|up\.(browser|link)|vodafone|wap|windows (ce|phone)|xda|xiino/i.test(navigator.userAgent) 
            || /1207|6310|6590|3gso|4thp|50[1-6]i|770s|802s|a wa|abac|ac(er|oo|s\-)|ai(ko|rn)|al(av|ca|co)|amoi|an(ex|ny|yw)|aptu|ar(ch|go)|as(te|us)|attw|au(di|\-m|r |s )|avan|be(ck|ll|nq)|bi(lb|rd)|bl(ac|az)|br(e|v)w|bumb|bw\-(n|u)|c55\/|capi|ccwa|cdm\-|cell|chtm|cldc|cmd\-|co(mp|nd)|craw|da(it|ll|ng)|dbte|dc\-s|devi|dica|dmob|do(c|p)o|ds(12|\-d)|el(49|ai)|em(l2|ul)|er(ic|k0)|esl8|ez([4-7]0|os|wa|ze)|fetc|fly(\-|_)|g1 u|g560|gene|gf\-5|g\-mo|go(\.w|od)|gr(ad|un)|haie|hcit|hd\-(m|p|t)|hei\-|hi(pt|ta)|hp( i|ip)|hs\-c|ht(c(\-| |_|a|g|p|s|t)|tp)|hu(aw|tc)|i\-(20|go|ma)|i230|iac( |\-|\/)|ibro|idea|ig01|ikom|im1k|inno|ipaq|iris|ja(t|v)a|jbro|jemu|jigs|kddi|keji|kgt( |\/)|klon|kpt |kwc\-|kyo(c|k)|le(no|xi)|lg( g|\/(k|l|u)|50|54|\-[a-w])|libw|lynx|m1\-w|m3ga|m50\/|ma(te|ui|xo)|mc(01|21|ca)|m\-cr|me(rc|ri)|mi(o8|oa|ts)|mmef|mo(01|02|bi|de|do|t(\-| |o|v)|zz)|mt(50|p1|v )|mwbp|mywa|n10[0-2]|n20[2-3]|n30(0|2)|n50(0|2|5)|n7(0(0|1)|10)|ne((c|m)\-|on|tf|wf|wg|wt)|nok(6|i)|nzph|o2im|op(ti|wv)|oran|owg1|p800|pan(a|d|t)|pdxg|pg(13|\-([1-8]|c))|phil|pire|pl(ay|uc)|pn\-2|po(ck|rt|se)|prox|psio|pt\-g|qa\-a|qc(07|12|21|32|60|\-[2-7]|i\-)|qtek|r380|r600|raks|rim9|ro(ve|zo)|s55\/|sa(ge|ma|mm|ms|ny|va)|sc(01|h\-|oo|p\-)|sdk\/|se(c(\-|0|1)|47|mc|nd|ri)|sgh\-|shar|sie(\-|m)|sk\-0|sl(45|id)|sm(al|ar|b3|it|t5)|so(ft|ny)|sp(01|h\-|v\-|v )|sy(01|mb)|t2(18|50)|t6(00|10|18)|ta(gt|lk)|tcl\-|tdg\-|tel(i|m)|tim\-|t\-mo|to(pl|sh)|ts(70|m\-|m3|m5)|tx\-9|up(\.b|g1|si)|utst|v400|v750|veri|vi(rg|te)|vk(40|5[0-3]|\-v)|vm40|voda|vulc|vx(52|53|60|61|70|80|81|83|85|98)|w3c(\-| )|webc|whit|wi(g |nc|nw)|wmlb|wonu|x700|yas\-|your|zeto|zte\-/i.test(navigator.userAgent.substr(0,4))) { 
            isMobile = true;
        }

        if (isMobile === false) {
            $('.github').mouseenter(function() {
                $('.gh').addClass('fade-in')
            })

            $('.gh').on('animationend', function() {
                if ($(this).hasClass('fade-in')) {
                    $(this).css('opacity', 1)
                    $(this).removeClass('fade-in')
                } else if ($(this).hasClass('fade-out')) {
                    $(this).css('opacity', 0)
                    $(this).removeClass('fade-out')
                }
            })

            $('.github').mouseleave(function() {
                $('.gh').addClass('fade-out')
            })

            $('.github').click(function() {
                window.open('https://github.com/ohitszenqi', '_blank').focus()
            })


            // Facebook

            $('.facebook').mouseenter(function() {
                $('.fb').addClass('fade-in')
            })

            $('.fb').on('animationend', function() {
                if ($(this).hasClass('fade-in')) {
                    $(this).css('opacity', 1)
                    $(this).removeClass('fade-in')
                } else if ($(this).hasClass('fade-out')) {
                    $(this).css('opacity', 0)
                    $(this).removeClass('fade-out')
                }
            })

            $('.facebook').mouseleave(function() {
                $('.fb').addClass('fade-out')
            })

            $('.facebook').click(function() {
                window.open('https://www.facebook.com/sean.ariate', '_blank').focus()
            })
        } else {
            $('.github').click(function() {
                window.open('https://github.com/ohitszenqi', '_blank').focus()
            })

            $('.facebook').click(function() {
                window.open('https://www.facebook.com/sean.ariate', '_blank').focus()
            })
        }
        const pics = [
            './pictures/0.png',
            './pictures/1.png',
            './pictures/2.png',
            './pictures/3.png',
            './pictures/4.png',
            './pictures/5.png',
            './pictures/6.png',
            './pictures/7.png',
            './pictures/8.png',
            './pictures/9.png',
        ]

        let index = 0
        $('.arrow-1').click(function() {
            const cpic = $('#hehe')
            const arrow1 = $('.arrow-1')
            const arrow0 = $('.arrow-0')
            const chrm = $('.chrm')
            if (cpic.attr('src') === pics[0]) {
                arrow0.css('visibility', 'visible')
            }

            if (cpic.attr('src') !== pics[9]) {
                index += 1
                $('#hehe').attr('src', pics[index])
            }

            if (cpic.attr('src') === pics[9]) {
                arrow1.css('visibility', 'hidden')
                chrm.css('top', '760px')
                
            }

            if (cpic.attr('src') !== pics[0]) {
                arrow0.css('visibility', 'visible')
            }
        })

        $('.arrow-0').click(function() {
            const cpic = $('#hehe')
            const chrm = $('.chrm')
            const arrow1 = $('.arrow-1')
            const arrow0 = $('.arrow-0')
            if (cpic.attr('src') === pics[0]) {
                arrow0.css('visibility', 'visible')
            }

            if (cpic.attr('src') !== pics[0]) {
                index -= 1
                $('#hehe').attr('src', pics[index])
            }

            if (cpic.attr('src') === pics[0]) {
                arrow0.css('visibility', 'hidden')
            } else {
                arrow0.css('visibility', 'visible')
            }

            if (cpic.attr('src') !== pics[9]) {
                arrow1.css('visibility', 'visible')
                chrm.css('top', '730px')
            }
        })


        $(document).ready(function() {
            const chrm = $('.chrm')
            let today = new Date();
            let christmasYear = today.getFullYear();

            if (today.getMonth() == 11 && today.getDate() > 25) {
            christmasYear = christmasYear + 1;
            }

            let christmasDate = new Date(christmasYear, 11, 25);
            let dayMilliseconds = 1000 * 60 * 60 * 24;

            let remainingDays = Math.ceil(
            (christmasDate.getTime() - today.getTime()) /
            (dayMilliseconds)
            );

            chrm.text(remainingDays + " Days before christmas!    ")
        })
    </script>
</body>
</html>
