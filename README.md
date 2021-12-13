# Shreya_Manav_Project
<!DOCTYPE html>   
<html>
    <head>
        <meta http-equiv="Content-Type" content="text/html;charset=UTF-8">
        <meta http-equiv="X-UA-Compatible" content="ie=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="style.css">
        <link href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">
        <link rel="shortcut icon" type="image/x-icon" href="https://i.pinimg.com/originals/a2/5f/4f/a25f4f58938bbe61357ebca42d23866f.png" sizes="32x32"/>
        <link href="https://fonts.googleapis.com/css?family=Roboto&display=swap" rel="stylesheet">
        <title> Instagram Clone</title>
    </head>

    <body>
        
        <div class="top">
            <div class="top-items">
                <div class="logo-area">
                   <a href="#"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2a/Instagram_logo.svg/1200px-Instagram_logo.svg.png" alt="logo" width="103"></div></a>
                </div>

                <div class="search-box sb">
                    <input type="text" class="search" placeholder="search">
                    <span class="ic"><img src="https://cdn2.iconfinder.com/data/icons/font-awesome/1792/search-512.png" alt="search" height="10px"></span>
                </div>

                <div class="acct-actions">

                    <div class="actions">
                        <a href="#" class="li">
                            <img height="24px" src="https://static.thenounproject.com/png/17705-200.png" alt="explore">    
                         </a>
                        <a href="#" class="li">
                           <img height="24px" src="https://cdn.iconscout.com/icon/free/png-512/explore-1781524-1513844.png" alt="explore">
                        </a>
                        <a href="#" class="li">
                            <img height="24px" src="https://www.pinclipart.com/picdir/big/33-337369_heart-shaped-clipart-instagram-heart-sign-icon-transparent.png" alt="love">
                         </a>
                         
                         <a href="#" class="li">
                            <img height="24px" src="https://pbs.twimg.com/profile_images/1017823687804882944/YMzUeY9d_400x400.jpg" alt="user" style="border-radius: 50%">
                         </a>
                    </div>
                </div>
            </div>
        </div>

     

        <!-- Body of the page -->

        <div class="main">

            <div class="statuses full">
                <div class="status">
                    <div class="status-ride">
                        <div class="status_">
                            <div class="status-pix">
                                <a href="#">
                                    <img class="pix" src="data:image/jpeg;base64,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" alt="user">
                                </a>
                            </div>
                            <div class="profile-link">
                                <a href="#">pst_iren</a>
                            </div>
                        </div>

                        <div class="status_">
                            <div class="status-pix">
                                <a href="#">
                                    <img class="pix" src="https://scontent-yyz1-1.cdninstagram.com/v/t51.2885-15/sh0.08/e35/s640x640/62023616_638623226635197_7956289733882868130_n.jpg?_nc_ht=scontent-yyz1-1.cdninstagram.com&_nc_cat=109&_nc_ohc=X0PmOkc_Dm4AX_ctPGl&oh=d98528a987ce5e7a20dd3c7f82ee73f4&oe=5EC9B663" alt="user">
                                </a>
                            </div>
                            <div class="profile-link">
                                <a href="#">simpl...</a>
                            </div>
                        </div>

                        <div class="status_">
                            <div class="status-pix">
                                <a href="#">
                                    <img class="pix" src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBxAQEBAQEBAVEBAVEBIbDRUVEBsQEA4WIB0iIiAdHx8kKDQsJCYxJx8fLTItMSxAMDBEIytKTT81QDQ5QzUBCgoKBQUFDgUFDisZExkrKysrKysrKysrKysrKysrKysrKysrKysrKysrKysrKysrKysrKysrKysrKysrKysrK//AABEIAMgAyAMBIgACEQEDEQH/xAAbAAABBQEBAAAAAAAAAAAAAAAFAAECBAYDB//EADwQAAEDAgQDBQUIAgEEAwAAAAEAAgMEEQUSITEGQVETIjJhcQdCgbHBFCMzUpGh0eFDYvByosLxFSQ0/8QAFAEBAAAAAAAAAAAAAAAAAAAAAP/EABQRAQAAAAAAAAAAAAAAAAAAAAD/2gAMAwEAAhEDEQA/ANknASToEqGOfgP9EQsh2PutTyehQeRVx0+Ki0J6zl6pNQOAouC6BMUDWSap2TXABJ25oEAmkeBuQPVD6nENw3bqhss5J3uet0Bo1cf5gnbVRnQOHyWcL1Av1QaltjspWWYjqHN2JCJUmL30k/UICpCiBqpsIIBBuDsU1tUEHDVRIXQqLgggQnAUikg52UgEiEggRCScpIPck4SKcIHQniU//Xk9Ci6DcU//AJ3+hQeTVXL1TtTVR1HqnCCYTWUmpgEDvNhcoPXVZdoPD81bxWewyjnugkrrWCBSO0+a5Ei/qrMeHyO1tpyXQ4S7cmyAYXhMXonHgxO6afB3t1A0QDbprrpLSOaq5ugI4fiLozY6tO4WiieHC4NwdljA5GMAqyHdmTofD5FAdIXM7rqQoW1QM5PZKylZBzISATkJBAiEk5SQe4lIBOUggcINxP8AgOHkjSA8WPtA4oPKa4d4eqm0KNb4m+q6AIJAJAJwE7UAbFDd6bC6DPICQd1ZMBfKdNA4LVYbhovmtY/pdBB2Hi1tlVnpAOS0T49lXqIxYoM4W220XCeQ2RCpitdC59EFKWK6py04O4Vx71Xe5ALrqXKA4bc1xopMsjD/ALBE6kXaUMyWIPmg2QUF1ZsPRQIQMFJME5QcykAncE4QJySdySD3ByQScnaEDrOcZ/gFaUBZrjZ33QHmg8urPG1dQFyqvxAu4CBwnskAnsgjhMWaV/I3v6rXU5005LOUlMWSh4N43nuOB3R2aYNF7XPIdSgsyFDqh9lQq8Sl1OgAGgte6HO4gubOaPUICr3g3CBYiNVYFY1wJafUdFxncHfVAMc0rhIFeqZWtCFzVrel0HRuuipVMVjfldW6WYONtrqc0WaWNnV2vogPgaD0UCuhXMoE1OUmpXQRckEinsgRCSdJB7gUmhJOEEgstxw3uArUrJ8dS9wNCDzSf8QKwFwk/E+CsBA7VOMagdSFEKdMe+z/AKh80F3DpIwHU7Lu7JzDmvuSdUQqXd2+3wVXBaTsxMDqe10cRbONCr7xcaIM3U4m/vgR2AF3FwsLfG1/hdZiWofIXuEdwD3iPPZa/GKmQAsIDx5hZplC95Ia3KCdbEhA2HS5jaxup10pjJvoj+F4f2drj1JN7oPxUM0lwNLIAMkrpCmLGtJBBuN7i1lbwuUxEnXVpGwOh9QubmC5IzG+97oOdORmBHVGIGXnBFtG69QELENtctkVpR9+T1iF/wBkBJQcui5OQSCYJ0yBgpKDVNAkk6SD28pBOU4QOFkuO7ZAtcFiuPnaNHmg88f+J8FZCrn8QqxZA9k8by1zXDcEFJRKAzFXOllboGsDTpzJRSlY2xuVnsPdZ4P+rvkr/wBpsL+SCeIQR3ubBU4mxuvlFwNShlTMZn2vYX7yLYfCIbPbbYixOhQQfUssQy9xyIQHE+/uNUdkxaIOIMQBP7oPidQNTYBAEa22u45rvG9p1CrPrG6gEarjEbbFBcksSr9JGc5dyygDzQlr7kI7S+Bvog7lcjuuhXPmgcpmpFM0oE1SUWqSB0kkkHuNkgnskEDhYj2g7N9VuFhPaCdWBBgGfiFW7KowfeFW7oHTKXJRG6DrE/K4HoVYlHib1HdKqOV99M9kUb3AgkXbfmL6IAVPA+No0LiARYcyiuDyCoDwI5btIzi2rNzy9CpsAOvnqjGEva1+YHI7k4c/IoAGMUkZBAu14Ot9wVmqqm0s55PwXsc+OxBpE9KyY3eb2GpI3WWxCvpMndoG5w6+bMBpe/Tog83+yAAkAkDc2XOA3JI2sjmMVnaaWDG62a3be+qGhugAQNAwucGjclaS1gANgFTwukyjORqfD5BXnIEVz5ro5cwgYpwkUmlAzU90mpc0Eikk5JB7mnsknAQJYD2hHvMXoFl577QvGzogw0fjKskqtH4irBHJBO6gN0dwzhaqneyPJ2ZcLjP3bDrbdW8VoYaVzmxNziNv3krnWzOGl7chf5II8IYL2sr5ZWHsYY3PcCLB5Gw9Lq5xE5pkfG29mMjDr73LA4n9SrPC1dNJDVF2rfsl33Or+8FV4wqCMSka9uQS08D4h1Fsp+SDNPd2Z12VtjSRmGoKhVxhwIIVWFz4Ra92fu1A+IOmbqCCOV90DnrJnAjKAPVEa/EARa4tfRCjXC1uaCk9h3O6g14Fut9fJPUTHkqkpsCg1NJVdoxryA05g0gfmtp+q6ygg2IseYKEcNuDw4F2UZf+8aj5ItgVU6qI+1TBoOkHdGYoESoAqzXU3ZuIDg8DmND8QdVUagclMCokpgdEE4ypDdc4ipjdBN2yS5yyBouUkHvKklZSsgiV577QJBmaN1voqmN73Rh4zNHf55Vi8VEc9c2ASZAHWc4s721za+yDLYbw1M6N1TKRDBycdXv1tYN9eq3XDGDRU1LJXFgLrWgL9La2ulxxicUHYU/aWjDWlrGjfWwuVR47r4exgax1hnsBmOlh5oNBNJ2VBJOJyah9jK5visTYAegKxOI0kD8Nlyvd2jmOzkm97E2C1BEUWFCR7sxcyIAA353+i8/xuvaKWNg7old3ztoCdP8AnRAT9mz3OZUF7+42jlu2/iItYfquvtXhmMOGYpyy9lIBu3S4/cOVr2d4I2mqntneCyaizxW5kmxHwReLDX4phldRSd18JcYB/sLkfuDr5oPPYK8PAN+SRnG3IrJYXWlvcPJG2Tg6oI1zGk6jTyQeSIX0vZGJrEXvqqEzAEFUsVWrGivuOiH1RQHeCqLtYqojdgYR6i5HyUKlwbLHUMbbv9wDwtAW29jOGh1PUSEby5TpyA/tAcXYImyxBmXLVAee5CCeK1TZsRjYQQCGNJG+tyVfqcIYDIGuvksS4C+h6t3+IQ6vrY2YjE/L70d9B6IlxLiEcE8VRExwe4EPAdlabW/lACkbbzHIjYrmNltMQqWMbFla3spSA/tGZshO2oQXFMBfETYtN9WNa7Nm9EAeFTG6ixhFwQQRuCLFO06oGq4czbBJdwkg93KTmB8c4JyZA4Pdfwm17DzsqWKVroI3TNbctOWEWvmkPP4BcKSSOCAR1dxNM2UuOou4tvY/sPUoBHAZia+oc9zpMuSw2bc31t8ELgxeFuJPPZA9+be3mi/COKRsbMWsuLsuduv8FZSir2nE5QW6F043v1KDnxdibKmvhYW2A7MHT/a6v8U0UTzAC+w75Pe9EOkjgdirM2gzs8vd/lHeNo6aN0Pev92fe53QGeLhTQYdFGDctdGNidmlY6tgp5cKubBzRdpsdDnWo41ED6RpzC3aM949CgEtHC7C+673HX73R5KCngVdI6WknLi6KJrhJb3WkjMPjqvTJ6ymbXQOheAyZuSYDa9gWn46fsvP8Dw2N1A8RSWla6QDUG9xex8iiPCM1DPTyvkFqyOHKx2cgG2jTbqNB+iDzn2m4IKHFKiJn4bnCSL0dqR8DcIVRzEhbz2l1Qq6eCvkgAs8wubciUOAJu48tiQPNYnDMIqJGmSGJzmc9Nv5QKR6gG3Sdr5HmiVNSt7Iu3cdAEAeS5Nk9FhMtS8RwtzOJ5kNaPiVv+HeDYnRGprJBHFY9ky9nzH529N1frMWoMHLZGUzZps3dYJDnjNr3de4b6DX0Qarh6niwPDGNqtA1pdK4f5JHE91o3J2C8z4lxhkwjlEeQTVOe17kNubA/AhduKOJZ62lE04sXltmg9xgvewHwVPihzBFSjLbKLbeQQQ4tdEJ4ZALd0X7vQo1xbLC6GJ4bs/8nIj+ly4qjp308EobzF9DsRf6ItX/ZX4Y19gSI4ydDuCAUE6qtjmwwfd3IiaeW7f/RVOkb9uoRYETxu7pG9x/SJ8IV8L6J0YZsZGjugbi/1Q3gbGTnnYG8mG1/UIJP7Otp7tLhURj7wOaLv+KzUlJYZ2kPYeY3aehHJaLBquSHEJI+z7rnSA6H1CbsBJNURtblkjJc1vKWN2pb+/wQZwJLtURBriBqPd62SQerV9S81lNTObdsTc8ota7jqfp+qpcQ4nHVVrIXAhrC0O6D3na/siOA4q2Stq5XNNg7KDuN7f+KHYbSwzyVM4IBLiG20OpudPgEDcMVENLWTUXiEjD2dudtW6+hKzMdVHFi7mvZp2r+Q95p/lcIcQEda6ocQ5sUrQw/6tNrW8/qiPGFXTuxKnqGAZJDA6+XcaD6IKfFxhZiFNJbKDkubW2d/Ct+0GCAspnNdc2eD3h5KHtE+zkU5Fh+IOY6LpxNh8M2HxzB3ea2N3i62B+aAhjGHxvw1r858MLvEPIfVNw1h1PLQvjL+crfEOev1VajpmT4S4Nk1bEQdL6sP9JvZ5hgdFMO02kB8PUf0g4ez0wB08b3Cxa0jv9Db6qkyhpY8TkjLgGPkIte9r95p/Wy6cJYQ1tfJGXkaSjYDY/wBJcTYdHHiURLzq6E+IdQPoglxXRyRRVnZZZo5ZIZGttmMcgJa42PUOOvkgfDmC17nZXvMbHci8j00C2HG0TacQyRvFyXhwLrtcNDqPUBVuIaVktAJ3zkOMcZ7r8gBuOQQAcU4Rhhkd2lY1hIuSQLNPnr1UMEwI2dJUTxQUzXWbLnDxMejANSiOA4ZRtw+eaVokyl4AD7OfcDS/qUF4bwuetnZJWZmQDSBtskbRfQNGwHzQF8R40igAgo4i6Z9g6plGZ7AdO6OR+SG8Wwxtji0Ny83OXyV/iXC6aOtiFxYNj97zR3j2npWwxHTSTzPJBmOJKiH7BSNDbX7K/d/1RPjhtN9liIAB7Qe6fylBOIHQup6S1rW8+QC0fHEFOaSIgjWRnvf6lByxOOmOFMOlwyHr1AXbCIqd+FOBIv2cvM8iV2nw+B+EA5hcQxnxdCF14MoqeShewv1DpB4uo/tBz4AqaVsUzQASHtPhJ3H9IdwhXxxYhM0MOvaAaAbG/wBFY9nrKYPnYSD3WHxE7E/yp0U9PFi5Abe8j7Wb1aTz9UHDH8Qc3E4yGWaS1x+Df6Q/iSd8UsVZGLFxDZP+eYRPjXFAMQbLks2OmJ394kgLk1jKvDm278rR/wB45eZI+aCpxHh3Zlrvztzjprv9D8Skh8uITPZTtlBsBK1pPIAaD/nROg9O4Yng+yTyusHEyG5FjoOvrdVI8Ny4XJPG6xb2jhzvYC2qsSUMTcKuw2JjGxv43f2quKQSU2BOc03zdDbd/T0QYzginL4qsTDMJG5Gk7g7kg+uU/BTlnppYYWXHaQOsDm8TL3H6G/7KGF174MOkkc3RxflNuthdBsPpWAMedGyktjN99dbfGyDYcfUMRhhId/kcPF5f0rz8OZJhFw43+zt5jlb+FW4+we1Mx2bQSM93a4KnhGFl2FkZx+DMNvNyCHAuENlppmZzbORt1aFS9n9EWTVMBfYgDl+UkfVWfZthziKhucAB0Z29f4VHC8Me3FZGtkteSYHz3P0Qd6fCuzxa2feV/u/mB8/NL2gYXlqIXFxH3Y5dHFccWoJI8ViLn+J8RFydtj8lf8AaThDrU5Lx/kG3ogs8eYa11PFd5uJBbTcWKhUYW12Ck5iSIfLk5c+I8Kc/DGSZ+81sLhp1sPqpYJhpkwqQZx+FNcW2IJQR4NwJtRhzmXzHtXEt/Naxt+y5VfELHvhoo92vZ2rmjex2CHcICSKCpyvOlyMt82reX6I1hfDApQa6QgPyn0hBG/qgq+0LCI2TU78xu5juYGx/tFuOsPgNC1+bUOjPiHMH+UO47wQllI8vFiH+71A/hXeJMNDsJzZ7nsoD4fMIMTilHGaGncHa5rbjz/haLiDCmuw2F+Y6NhO46W+qzVXh18Ohdm/ydPNy1dXgpfhDXZ9oYz4ehCC5hGEskwk9837GUcuRKq+z2ij7OZpedHtO45j+lY4HwkyUD25/ekFsvUf2hXs9wy8k4L/AHWHbzKB+DqGFlfMwusMsg8Q5OCv1bKWHFmGwcS6M83e7ZVcCwYDF3tLjYySg6W5EhWuLvstNXseSCQIud/kgq8ROFdUTRsFge646Cwtp+5KFcJYm3DoKvM0PmY28QOzH6i/yVXgqpmq8RqMgyRf5HW8AB0+J1U4qUSivyAvdnlGYm98pNvkg74TRST0TZ5jcl9x1vmKSr4RXy9gIHd1pmbYWtplJ/8AFJBv+NMPLKSNrH2+9aNdNA0rhxSZ48DjY7X8O99d7lJJBlaPG4xhX2eVos5ha072Jcb/AFQaCgD4YIXHK4Od9nN/EdSR8bfJJJBveLsMkkwpsrXXBZAdz5IZw3HOcPLQ46NmB73qfqkkg4+ziGoL6gAnaO/e9Vxp6ecYvub9vJ7/AJFJJBL2gU07KinkzG4YCDm6OJVvj2Gd0EDnOOkhHi6j+kkkEqimndhN83+GP3jyITcH0sxopBm0zSjxnYtCSSANwHHIZZMz7MBjLzmuANblWZ8bnrqltFGD2WezQdifzO8kkkBPjejmFNTgvuWkDxH8qjV0Upwgku0+ztI7x6hJJBlnUcpwyMh2gf8AmP5iPqtfh1BO/B3d/TsJB4jyJSSQcvZ5BKYJm57WkHvHmP6Q7gWhl+2TtDtMruZ5OSSQFKDAn/8AzOr7DPfr7iEe1enjjrGgEuJYzS++6SSDK8O4tJTfayBlBjde2gvyWu9m9awUc5yF5aZC7z7t0kkGajnke6CUizTORoNLBtvqUkkkH//Z" alt="user">
                                </a>
                            </div>
                            <div class="profile-link">
                                <a href="#">fagbs_id</a>
                            </div>
                        </div>

                        <div class="status_">
                            <div class="status-pix">
                                <a href="#">
                                    <img class="pix" src="https://mir-s3-cdn-cf.behance.net/user/276/a217775903389.550d7721899d8.jpg" alt="user">
                                </a>
                            </div>
                            <div class="profile-link">
                                <a href="#">adekun...</a>
                            </div>
                        </div>

                        <div class="status_">
                            <div class="status-pix">
                                <a href="#">
                                    <img class="pix" src="https://is5-ssl.mzstatic.com/image/thumb/Music113/v4/74/f2/c2/74f2c2b7-842d-3af6-1ba2-d4563b897c8f/pr_source.png/800x800bb.jpeg" alt="user">
                                </a>
                            </div>
                            <div class="profile-link">
                                <a href="#">iamjode..</a>
                            </div>
                        </div>
                        
                        <div class="status_">
                            <div class="status-pix">
                                <a href="#">
                                    <img class="pix" src="https://dailypost.ng/wp-content/uploads/2019/06/Biodun-fatoyinbo.jpg" alt="user">
                                </a>
                            </div>
                            <div class="profile-link">
                                <a href="#">biodu...</a>
                            </div>
                        </div>

                        <div class="status_">
                            <div class="status-pix">
                                <a href="#">
                                    <img class="pix" src="data:image/jpeg;base64,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" alt="user">
                                </a>
                            </div>
                            <div class="profile-link">
                                <a href="#">jjhairs...</a>
                            </div>
                        </div>

                        <div class="status_">
                            <div class="status-pix">
                                <a href="#">
                                    <img class="pix" src="https://is5-ssl.mzstatic.com/image/thumb/Music113/v4/74/f2/c2/74f2c2b7-842d-3af6-1ba2-d4563b897c8f/pr_source.png/800x800bb.jpeg" alt="user">
                                </a>
                            </div>
                            <div class="profile-link">
                                <a href="#">iamjode..</a>
                            </div>
                        </div>
                        
                        <div class="status_">
                            <div class="status-pix">
                                <a href="#">
                                    <img class="pix" src="https://dailypost.ng/wp-content/uploads/2019/06/Biodun-fatoyinbo.jpg" alt="user">
                                </a>
                            </div>
                            <div class="profile-link">
                                <a href="#">biodu...</a>
                            </div>
                        </div>

                        <div class="status_">
                            <div class="status-pix">
                                <a href="#">
                                    <img class="pix" src="data:image/jpeg;base64,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" alt="user">
                                </a>
                            </div>
                            <div class="profile-link">
                                <a href="#">jjhairs...</a>
                            </div>
                        </div>


                    </div>

                </div>
        </div>
        
            <div class="section">

               <div class="top-section">

                    <div class="section-title">

                        <div class="profile-pic">

                            <a href="#">
                                <img class="picture" src="data:image/jpeg;base64,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" alt="user">
                            </a>
    
                        </div>
                        
    
                        <div class="profile">
    
                            <a href="#" class="profile_tag">pst_iren</a>
    
                        </div>

                    </div>
                  
                    
                    
                    <div class="opt">
                        <a href="#" class="options">
                            <div class="op"></div>
                            <div class="op"></div>
                            <div class="op"></div>
                        </a>
                    </div>
               </div>

                    <div class="upload"> 
                        
                        <img class="upload-content" src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTBXEZnYDFnSS5mX8i9LCJAh0iAvaztg9wPKonWMlOi_yn7Hs2w">
                    </div>

                    <div class="upload-actions">
                
                       <button class="u-actions-li">
                           <a href="#">
                               <img height="28px" src="https://www.pinclipart.com/picdir/big/33-337369_heart-shaped-clipart-instagram-heart-sign-icon-transparent.png" alt="">
                           </a>
                       </button>
                       <button class="u-actions-li">
                            <a href="#">
                                <img  height="28px" src="https://cdn0.iconfinder.com/data/icons/instagram-ui-1/24/Instagram-UI_comment-512.png" alt="">
                            </a>
                        </button class="u-actions-li">
                        <button class="u-actions-li">
                            <a href="#">
                                <img  height="28px" src="https://qph.fs.quoracdn.net/main-qimg-094b6418c35690a0a9425642728f081b" alt="">
                            </a>
                        </button>
                        <button class="u-actions-li aside-tag">
                            <a href="#">
                                <img class="tag" height="28px" src="https://cdn.clipart.email/51d663379c2127f9240f6b677bce03a2_flag-instagram-interface-save-tag-icon_512-512.png" alt="">
                            </a>
                        </button>
                    </div>

                    <div class="liked">
                        <p class="liked-count">
                            Liked by <a class="likes" href="#">olife_onyinye</a> and <button class="others">others</button>
                        </p> 
                    </div>

                    <div class="upload-caption">
                        <span class="post">
                            <a href="#" class="likes">pst_iren</a>
                            <span class="post-link">
                                Yesterday in pictures. Great services in ABUJA and LAGOS. What a month
                                this has been.
                            </span>
                        </span>
                            
                    </div>


                    <div class="upload-caption comments liked">
                        <a class="likes comment" href="#">View all <span>58</span> comments</a>
                    </div>

                    <div class="upload-caption comments">
                        <span class="post">
                            <a href="#" class="likes">justified_kay</a>
                            <span class="post-link">
                                Yesterday was awesome! It's a year of movement!
                            </span>

                            <span class="post-link"> 
                                <button class="u-actions-li  like">
                                    <a href="#" class="push2">
                                        <img height="12px" src="https://www.pinclipart.com/picdir/big/33-337369_heart-shaped-clipart-instagram-heart-sign-icon-transparent.png" alt="">
                                    </a>
                                </button>
                            </span>
                        </span>
                            
                    </div>

                    <div class="upload-caption comments">
                        <span class="post">
                            <a href="#" class="likes">_ginnie</a>
                            <span class="post-link">
                                It was a great experience.
                            </span>
                            
                            <span class="post-link"> 
                                <button class="u-actions-li  like">
                                    <a href="#" class="push">
                                        <img height="12px" src="https://www.pinclipart.com/picdir/big/33-337369_heart-shaped-clipart-instagram-heart-sign-icon-transparent.png" alt="">
                                    </a>
                                </button>
                            </span>
                        </span>
                  
                    </div>

                    <div class="time-stamp liked">
                        18 HOURS AGO
                    </div>

                    <div class="submit">
                        <div class="">
                            <form class="ssub" method="POST">
                                <input type="text" placeholder="Add a comment…" class="texta">

                                </input>
                                <button class="button u-actions-li">Post</button>
                            </form>
                        </div>
                    </div>

                    
            </div>

            <div class="section section2">

                <div class="top-section">
 
                     <div class="section-title">
 
                         <div class="profile-pic">
 
                             <a href="#">
                                 <img class="picture" src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSB-uKOK8M_Goa1J6xoOlFkKbSXGf6c0EMXzuvfAvQOqHXGI-F1" alt="user">
                             </a>
     
                         </div>
                         
     
                         <div class="profile">
     
                             <a href="#" class="profile_tag">babsadenuga</a>
     
                         </div>
 
                     </div>
                   
                     
                     
                     <div class="opt">
                         <a href="#" class="options">
                             <div class="op"></div>
                             <div class="op"></div>
                             <div class="op"></div>
                         </a>
                     </div>
                </div>
 
                     <div class="upload"> 
                         
                         <img class="upload-content" src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSB-uKOK8M_Goa1J6xoOlFkKbSXGf6c0EMXzuvfAvQOqHXGI-F1">
                     </div>
 
                     <div class="upload-actions">
                 
                        <button class="u-actions-li">
                            <a href="#">
                                <img height="28px" src="https://www.pinclipart.com/picdir/big/33-337369_heart-shaped-clipart-instagram-heart-sign-icon-transparent.png" alt="">
                            </a>
                        </button>
                        <button class="u-actions-li">
                             <a href="#">
                                 <img  height="28px" src="https://cdn0.iconfinder.com/data/icons/instagram-ui-1/24/Instagram-UI_comment-512.png" alt="">
                             </a>
                         </button class="u-actions-li">
                         <button class="u-actions-li">
                             <a href="#">
                                 <img  height="28px" src="https://qph.fs.quoracdn.net/main-qimg-094b6418c35690a0a9425642728f081b" alt="">
                             </a>
                         </button>
                         <button class="u-actions-li aside-tag">
                             <a href="#">
                                 <img class="tag" height="28px" src="https://cdn.clipart.email/51d663379c2127f9240f6b677bce03a2_flag-instagram-interface-save-tag-icon_512-512.png" alt="">
                             </a>
                         </button>
                     </div>
 
                     <div class="liked">
                         <p class="liked-count">
                             Liked by <a class="likes" href="#">akolade_olusola</a> and <button class="others">others</button>
                         </p> 
                     </div>
 
                     <div class="upload-caption">
                         <span class="post">
                             <a href="#" class="likes">babsadenuga</a>
                             <span class="post-link">
                                My name is Babatunde Adenuga and I am here to tell stories. 
                                To inspire stories. To lead powerful stories and to build stories 
                                that inspire hope and faith in the greatness of Africa.
                             </span>
                         </span>
                             
                     </div>
 
 
                     <div class="upload-caption comments liked">
                         <a class="likes comment" href="#">View all <span>35</span> comments</a>
                     </div>
 
                     <div class="upload-caption comments">
                         <span class="post">
                             <a href="#" class="likes">akolade_olusola</a>
                             <span class="post-link">
                                 Grandezo! 
                                 <!-- You're an inspiration to me, I love you very much! -->
                             </span>
 
                             <span class="post-link"> 
                                 <button class="u-actions-li  like">
                                     <a href="#" class="push2">
                                         <img height="12px" src="https://www.pinclipart.com/picdir/big/33-337369_heart-shaped-clipart-instagram-heart-sign-icon-transparent.png" alt="">
                                     </a>
                                 </button>
                             </span>
                         </span>
                             
                     </div>
 
                     <div class="upload-caption comments">
                         <span class="post">
                             <a href="#" class="likes">kenny_great</a>
                             <span class="post-link">
                                 The sun is the limit bro!
                             </span>
                             
                             <span class="post-link"> 
                                 <button class="u-actions-li  like">
                                     <a href="#" class="push push2">
                                         <img height="12px" src="https://www.pinclipart.com/picdir/big/33-337369_heart-shaped-clipart-instagram-heart-sign-icon-transparent.png" alt="">
                                     </a>
                                 </button>
                             </span>
                         </span>
                   
                     </div>
 
                     <div class="time-stamp  liked">
                         12 HOURS AGO
                     </div>
 
                     <div class="submit">
                         <div class="">
                             <form class="ssub" method="POST">
                                 <input type="text" placeholder="Add a comment…" class="texta">
 
                                 </input>
                                 <button class="button u-actions-li">Post</button>
                             </form>
                         </div>
                     </div>
 
                     
             </div>

             <div class="section section2">

                <div class="top-section">
 
                     <div class="section-title">
 
                         <div class="profile-pic">
 
                             <a href="#">
                                 <img class="picture" src="data:image/jpeg;base64,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" alt="user">
                             </a>
     
                         </div>
                         
     
                         <div class="profile">
     
                             <a href="#" class="profile_tag">thesamuelbello</a>
     
                         </div>
 
                     </div>
                   
                     
                     
                     <div class="opt">
                         <a href="#" class="options">
                             <div class="op"></div>
                             <div class="op"></div>
                             <div class="op"></div>
                         </a>
                     </div>
                </div>
 
                     <div class="upload"> 
                         
                         <img class="upload-content" src="https://pbs.twimg.com/profile_images/1230880902932303874/KHbTvA0N_400x400.jpg">
                     </div>
 
                     <div class="upload-actions">
                 
                        <button class="u-actions-li">
                            <a href="#">
                                <img height="28px" src="https://www.pinclipart.com/picdir/big/33-337369_heart-shaped-clipart-instagram-heart-sign-icon-transparent.png" alt="">
                            </a>
                        </button>
                        <button class="u-actions-li">
                             <a href="#">
                                 <img  height="28px" src="https://cdn0.iconfinder.com/data/icons/instagram-ui-1/24/Instagram-UI_comment-512.png" alt="">
                             </a>
                         </button class="u-actions-li">
                         <button class="u-actions-li">
                             <a href="#">
                                 <img  height="28px" src="https://qph.fs.quoracdn.net/main-qimg-094b6418c35690a0a9425642728f081b" alt="">
                             </a>
                         </button>
                         <button class="u-actions-li aside-tag">
                             <a href="#">
                                 <img class="tag" height="28px" src="https://cdn.clipart.email/51d663379c2127f9240f6b677bce03a2_flag-instagram-interface-save-tag-icon_512-512.png" alt="">
                             </a>
                         </button>
                     </div>
 
                     <div class="liked">
                         <p class="liked-count">
                             Liked by <a class="likes" href="#">akolade_olusola</a> and <button class="others">others</button>
                         </p> 
                     </div>
 
                     <div class="upload-caption">
                         <span class="post">
                             <a href="#" class="likes">thesamuelbello</a>
                             <span class="post-link">
                                Absolutely flawless!
                             </span>
                         </span>
                             
                     </div>
 
 
                     <div class="upload-caption comments liked">
                         <a class="likes comment" href="#">View all <span>53</span> comments</a>
                     </div>
 
                     <div class="upload-caption comments">
                         <span class="post">
                             <a href="#" class="likes">akolade_olusola</a>
                             <span class="post-link">
                                 El Patron...
                             </span>
 
                             <span class="post-link"> 
                                 <button class="u-actions-li  like">
                                     <a href="#" class="push2">
                                         <img height="12px" src="https://www.pinclipart.com/picdir/big/33-337369_heart-shaped-clipart-instagram-heart-sign-icon-transparent.png" alt="">
                                     </a>
                                 </button>
                             </span>
                         </span>
                             
                     </div>
 
                     <div class="upload-caption comments">
                         <span class="post">
                             <a href="#" class="likes">the_kendrick</a>
                             <span class="post-link">
                                 Boss boss...
                             </span>
                             
                             <span class="post-link"> 
                                 <button class="u-actions-li  like">
                                     <a href="#" class="push">
                                         <img height="12px" src="https://www.pinclipart.com/picdir/big/33-337369_heart-shaped-clipart-instagram-heart-sign-icon-transparent.png" alt="">
                                     </a>
                                 </button>
                             </span>
                         </span>
                   
                     </div>
 
                     <div class="time-stamp liked">
                         22 HOURS AGO
                     </div>
 
                     <div class="submit">
                         <div class="">
                             <form class="ssub" method="POST">
                                 <input type="text" placeholder="Add a comment…" class="texta">
 
                                 </input>
                                 <button class="button u-actions-li">Post</button>
                             </form>
                         </div>
                     </div>
 
                     
             </div>
 
            
                
               <!-- Aside section- Pc screen alone -->

            <div class="aside-section">

                <div class="aside1">

                    <div class="user-profile">
                        <div class="own-profile-pic">

                            <a href="#">
                                <img class="own-picture" src="https://pbs.twimg.com/profile_images/1017823687804882944/YMzUeY9d_400x400.jpg" alt="user">
                            </a>
    
                        </div>
    
                        <div class="user">
    
                            <a href="#" class="own-account">
                                <span class="identity">
                                    akolade_olusola
                                </span>
                                   
                                <span class="username">
                                    Akolade
                                </span>
                            </a>
    
                        </div>
                    </div>
    
                </div>
    
                <div class="aside2">

                    <div class="aside2-top">

                        <div class="aside2-top1">
                            Stories
                        </div>

                        <div class="aside2-top2">
                            <a href="#">Watch All</a>
                        </div>
                    </div>

                    <div class="aside2-body">

                        <div class="story">
                            
                            
                        <div class="profile-pic">

                            <a href="#">
                                <img class="picture" src="data:image/jpeg;base64,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" alt="user">
                            </a>
    
                        </div>
                        
    
                        <div class="profile-info">

                            <span class="profile-link">
                                <a href="#">pst_iren</a>
                            </span>
                           
                            <span class="time-stamp">
                                19 HOURS AGO
                            </span>
                        </div>

                        </div>
                        
                        <div class="story">
                            
                            
                            <div class="profile-pic">
    
                                <a href="#">
                                    <img class="picture" src="https://scontent-yyz1-1.cdninstagram.com/v/t51.2885-15/sh0.08/e35/s640x640/62023616_638623226635197_7956289733882868130_n.jpg?_nc_ht=scontent-yyz1-1.cdninstagram.com&_nc_cat=109&_nc_ohc=X0PmOkc_Dm4AX_ctPGl&oh=d98528a987ce5e7a20dd3c7f82ee73f4&oe=5EC9B663" alt="user">
                                </a>
        
                            </div>
                            
        
                            <div class="profile-info">
    
                                <span class="profile-link">
                                    <a href="#">simplynaza</a>
                                </span>
                               
                                <span class="time-stamp">
                                    2 HOURS AGO
                                </span>
                            </div>
    
                        </div>
                            
                        <div class="story">
                            
                            
                            <div class="profile-pic">
    
                                <a href="#">
                                    <img class="picture" src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBxAQEBAQEBAVEBAVEBIbDRUVEBsQEA4WIB0iIiAdHx8kKDQsJCYxJx8fLTItMSxAMDBEIytKTT81QDQ5QzUBCgoKBQUFDgUFDisZExkrKysrKysrKysrKysrKysrKysrKysrKysrKysrKysrKysrKysrKysrKysrKysrKysrK//AABEIAMgAyAMBIgACEQEDEQH/xAAbAAABBQEBAAAAAAAAAAAAAAAFAAECBAYDB//EADwQAAEDAgQDBQUIAgEEAwAAAAEAAgMEEQUSITEGQVETIjJhcQdCgbHBFCMzUpGh0eFDYvByosLxFSQ0/8QAFAEBAAAAAAAAAAAAAAAAAAAAAP/EABQRAQAAAAAAAAAAAAAAAAAAAAD/2gAMAwEAAhEDEQA/ANknASToEqGOfgP9EQsh2PutTyehQeRVx0+Ki0J6zl6pNQOAouC6BMUDWSap2TXABJ25oEAmkeBuQPVD6nENw3bqhss5J3uet0Bo1cf5gnbVRnQOHyWcL1Av1QaltjspWWYjqHN2JCJUmL30k/UICpCiBqpsIIBBuDsU1tUEHDVRIXQqLgggQnAUikg52UgEiEggRCScpIPck4SKcIHQniU//Xk9Ci6DcU//AJ3+hQeTVXL1TtTVR1HqnCCYTWUmpgEDvNhcoPXVZdoPD81bxWewyjnugkrrWCBSO0+a5Ei/qrMeHyO1tpyXQ4S7cmyAYXhMXonHgxO6afB3t1A0QDbprrpLSOaq5ugI4fiLozY6tO4WiieHC4NwdljA5GMAqyHdmTofD5FAdIXM7rqQoW1QM5PZKylZBzISATkJBAiEk5SQe4lIBOUggcINxP8AgOHkjSA8WPtA4oPKa4d4eqm0KNb4m+q6AIJAJAJwE7UAbFDd6bC6DPICQd1ZMBfKdNA4LVYbhovmtY/pdBB2Hi1tlVnpAOS0T49lXqIxYoM4W220XCeQ2RCpitdC59EFKWK6py04O4Vx71Xe5ALrqXKA4bc1xopMsjD/ALBE6kXaUMyWIPmg2QUF1ZsPRQIQMFJME5QcykAncE4QJySdySD3ByQScnaEDrOcZ/gFaUBZrjZ33QHmg8urPG1dQFyqvxAu4CBwnskAnsgjhMWaV/I3v6rXU5005LOUlMWSh4N43nuOB3R2aYNF7XPIdSgsyFDqh9lQq8Sl1OgAGgte6HO4gubOaPUICr3g3CBYiNVYFY1wJafUdFxncHfVAMc0rhIFeqZWtCFzVrel0HRuuipVMVjfldW6WYONtrqc0WaWNnV2vogPgaD0UCuhXMoE1OUmpXQRckEinsgRCSdJB7gUmhJOEEgstxw3uArUrJ8dS9wNCDzSf8QKwFwk/E+CsBA7VOMagdSFEKdMe+z/AKh80F3DpIwHU7Lu7JzDmvuSdUQqXd2+3wVXBaTsxMDqe10cRbONCr7xcaIM3U4m/vgR2AF3FwsLfG1/hdZiWofIXuEdwD3iPPZa/GKmQAsIDx5hZplC95Ia3KCdbEhA2HS5jaxup10pjJvoj+F4f2drj1JN7oPxUM0lwNLIAMkrpCmLGtJBBuN7i1lbwuUxEnXVpGwOh9QubmC5IzG+97oOdORmBHVGIGXnBFtG69QELENtctkVpR9+T1iF/wBkBJQcui5OQSCYJ0yBgpKDVNAkk6SD28pBOU4QOFkuO7ZAtcFiuPnaNHmg88f+J8FZCrn8QqxZA9k8by1zXDcEFJRKAzFXOllboGsDTpzJRSlY2xuVnsPdZ4P+rvkr/wBpsL+SCeIQR3ubBU4mxuvlFwNShlTMZn2vYX7yLYfCIbPbbYixOhQQfUssQy9xyIQHE+/uNUdkxaIOIMQBP7oPidQNTYBAEa22u45rvG9p1CrPrG6gEarjEbbFBcksSr9JGc5dyygDzQlr7kI7S+Bvog7lcjuuhXPmgcpmpFM0oE1SUWqSB0kkkHuNkgnskEDhYj2g7N9VuFhPaCdWBBgGfiFW7KowfeFW7oHTKXJRG6DrE/K4HoVYlHib1HdKqOV99M9kUb3AgkXbfmL6IAVPA+No0LiARYcyiuDyCoDwI5btIzi2rNzy9CpsAOvnqjGEva1+YHI7k4c/IoAGMUkZBAu14Ot9wVmqqm0s55PwXsc+OxBpE9KyY3eb2GpI3WWxCvpMndoG5w6+bMBpe/Tog83+yAAkAkDc2XOA3JI2sjmMVnaaWDG62a3be+qGhugAQNAwucGjclaS1gANgFTwukyjORqfD5BXnIEVz5ro5cwgYpwkUmlAzU90mpc0Eikk5JB7mnsknAQJYD2hHvMXoFl577QvGzogw0fjKskqtH4irBHJBO6gN0dwzhaqneyPJ2ZcLjP3bDrbdW8VoYaVzmxNziNv3krnWzOGl7chf5II8IYL2sr5ZWHsYY3PcCLB5Gw9Lq5xE5pkfG29mMjDr73LA4n9SrPC1dNJDVF2rfsl33Or+8FV4wqCMSka9uQS08D4h1Fsp+SDNPd2Z12VtjSRmGoKhVxhwIIVWFz4Ra92fu1A+IOmbqCCOV90DnrJnAjKAPVEa/EARa4tfRCjXC1uaCk9h3O6g14Fut9fJPUTHkqkpsCg1NJVdoxryA05g0gfmtp+q6ygg2IseYKEcNuDw4F2UZf+8aj5ItgVU6qI+1TBoOkHdGYoESoAqzXU3ZuIDg8DmND8QdVUagclMCokpgdEE4ypDdc4ipjdBN2yS5yyBouUkHvKklZSsgiV577QJBmaN1voqmN73Rh4zNHf55Vi8VEc9c2ASZAHWc4s721za+yDLYbw1M6N1TKRDBycdXv1tYN9eq3XDGDRU1LJXFgLrWgL9La2ulxxicUHYU/aWjDWlrGjfWwuVR47r4exgax1hnsBmOlh5oNBNJ2VBJOJyah9jK5visTYAegKxOI0kD8Nlyvd2jmOzkm97E2C1BEUWFCR7sxcyIAA353+i8/xuvaKWNg7old3ztoCdP8AnRAT9mz3OZUF7+42jlu2/iItYfquvtXhmMOGYpyy9lIBu3S4/cOVr2d4I2mqntneCyaizxW5kmxHwReLDX4phldRSd18JcYB/sLkfuDr5oPPYK8PAN+SRnG3IrJYXWlvcPJG2Tg6oI1zGk6jTyQeSIX0vZGJrEXvqqEzAEFUsVWrGivuOiH1RQHeCqLtYqojdgYR6i5HyUKlwbLHUMbbv9wDwtAW29jOGh1PUSEby5TpyA/tAcXYImyxBmXLVAee5CCeK1TZsRjYQQCGNJG+tyVfqcIYDIGuvksS4C+h6t3+IQ6vrY2YjE/L70d9B6IlxLiEcE8VRExwe4EPAdlabW/lACkbbzHIjYrmNltMQqWMbFla3spSA/tGZshO2oQXFMBfETYtN9WNa7Nm9EAeFTG6ixhFwQQRuCLFO06oGq4czbBJdwkg93KTmB8c4JyZA4Pdfwm17DzsqWKVroI3TNbctOWEWvmkPP4BcKSSOCAR1dxNM2UuOou4tvY/sPUoBHAZia+oc9zpMuSw2bc31t8ELgxeFuJPPZA9+be3mi/COKRsbMWsuLsuduv8FZSir2nE5QW6F043v1KDnxdibKmvhYW2A7MHT/a6v8U0UTzAC+w75Pe9EOkjgdirM2gzs8vd/lHeNo6aN0Pev92fe53QGeLhTQYdFGDctdGNidmlY6tgp5cKubBzRdpsdDnWo41ED6RpzC3aM949CgEtHC7C+673HX73R5KCngVdI6WknLi6KJrhJb3WkjMPjqvTJ6ymbXQOheAyZuSYDa9gWn46fsvP8Dw2N1A8RSWla6QDUG9xex8iiPCM1DPTyvkFqyOHKx2cgG2jTbqNB+iDzn2m4IKHFKiJn4bnCSL0dqR8DcIVRzEhbz2l1Qq6eCvkgAs8wubciUOAJu48tiQPNYnDMIqJGmSGJzmc9Nv5QKR6gG3Sdr5HmiVNSt7Iu3cdAEAeS5Nk9FhMtS8RwtzOJ5kNaPiVv+HeDYnRGprJBHFY9ky9nzH529N1frMWoMHLZGUzZps3dYJDnjNr3de4b6DX0Qarh6niwPDGNqtA1pdK4f5JHE91o3J2C8z4lxhkwjlEeQTVOe17kNubA/AhduKOJZ62lE04sXltmg9xgvewHwVPihzBFSjLbKLbeQQQ4tdEJ4ZALd0X7vQo1xbLC6GJ4bs/8nIj+ly4qjp308EobzF9DsRf6ItX/ZX4Y19gSI4ydDuCAUE6qtjmwwfd3IiaeW7f/RVOkb9uoRYETxu7pG9x/SJ8IV8L6J0YZsZGjugbi/1Q3gbGTnnYG8mG1/UIJP7Otp7tLhURj7wOaLv+KzUlJYZ2kPYeY3aehHJaLBquSHEJI+z7rnSA6H1CbsBJNURtblkjJc1vKWN2pb+/wQZwJLtURBriBqPd62SQerV9S81lNTObdsTc8ota7jqfp+qpcQ4nHVVrIXAhrC0O6D3na/siOA4q2Stq5XNNg7KDuN7f+KHYbSwzyVM4IBLiG20OpudPgEDcMVENLWTUXiEjD2dudtW6+hKzMdVHFi7mvZp2r+Q95p/lcIcQEda6ocQ5sUrQw/6tNrW8/qiPGFXTuxKnqGAZJDA6+XcaD6IKfFxhZiFNJbKDkubW2d/Ct+0GCAspnNdc2eD3h5KHtE+zkU5Fh+IOY6LpxNh8M2HxzB3ea2N3i62B+aAhjGHxvw1r858MLvEPIfVNw1h1PLQvjL+crfEOev1VajpmT4S4Nk1bEQdL6sP9JvZ5hgdFMO02kB8PUf0g4ez0wB08b3Cxa0jv9Db6qkyhpY8TkjLgGPkIte9r95p/Wy6cJYQ1tfJGXkaSjYDY/wBJcTYdHHiURLzq6E+IdQPoglxXRyRRVnZZZo5ZIZGttmMcgJa42PUOOvkgfDmC17nZXvMbHci8j00C2HG0TacQyRvFyXhwLrtcNDqPUBVuIaVktAJ3zkOMcZ7r8gBuOQQAcU4Rhhkd2lY1hIuSQLNPnr1UMEwI2dJUTxQUzXWbLnDxMejANSiOA4ZRtw+eaVokyl4AD7OfcDS/qUF4bwuetnZJWZmQDSBtskbRfQNGwHzQF8R40igAgo4i6Z9g6plGZ7AdO6OR+SG8Wwxtji0Ny83OXyV/iXC6aOtiFxYNj97zR3j2npWwxHTSTzPJBmOJKiH7BSNDbX7K/d/1RPjhtN9liIAB7Qe6fylBOIHQup6S1rW8+QC0fHEFOaSIgjWRnvf6lByxOOmOFMOlwyHr1AXbCIqd+FOBIv2cvM8iV2nw+B+EA5hcQxnxdCF14MoqeShewv1DpB4uo/tBz4AqaVsUzQASHtPhJ3H9IdwhXxxYhM0MOvaAaAbG/wBFY9nrKYPnYSD3WHxE7E/yp0U9PFi5Abe8j7Wb1aTz9UHDH8Qc3E4yGWaS1x+Df6Q/iSd8UsVZGLFxDZP+eYRPjXFAMQbLks2OmJ394kgLk1jKvDm278rR/wB45eZI+aCpxHh3Zlrvztzjprv9D8Skh8uITPZTtlBsBK1pPIAaD/nROg9O4Yng+yTyusHEyG5FjoOvrdVI8Ny4XJPG6xb2jhzvYC2qsSUMTcKuw2JjGxv43f2quKQSU2BOc03zdDbd/T0QYzginL4qsTDMJG5Gk7g7kg+uU/BTlnppYYWXHaQOsDm8TL3H6G/7KGF174MOkkc3RxflNuthdBsPpWAMedGyktjN99dbfGyDYcfUMRhhId/kcPF5f0rz8OZJhFw43+zt5jlb+FW4+we1Mx2bQSM93a4KnhGFl2FkZx+DMNvNyCHAuENlppmZzbORt1aFS9n9EWTVMBfYgDl+UkfVWfZthziKhucAB0Z29f4VHC8Me3FZGtkteSYHz3P0Qd6fCuzxa2feV/u/mB8/NL2gYXlqIXFxH3Y5dHFccWoJI8ViLn+J8RFydtj8lf8AaThDrU5Lx/kG3ogs8eYa11PFd5uJBbTcWKhUYW12Ck5iSIfLk5c+I8Kc/DGSZ+81sLhp1sPqpYJhpkwqQZx+FNcW2IJQR4NwJtRhzmXzHtXEt/Naxt+y5VfELHvhoo92vZ2rmjex2CHcICSKCpyvOlyMt82reX6I1hfDApQa6QgPyn0hBG/qgq+0LCI2TU78xu5juYGx/tFuOsPgNC1+bUOjPiHMH+UO47wQllI8vFiH+71A/hXeJMNDsJzZ7nsoD4fMIMTilHGaGncHa5rbjz/haLiDCmuw2F+Y6NhO46W+qzVXh18Ohdm/ydPNy1dXgpfhDXZ9oYz4ehCC5hGEskwk9837GUcuRKq+z2ij7OZpedHtO45j+lY4HwkyUD25/ekFsvUf2hXs9wy8k4L/AHWHbzKB+DqGFlfMwusMsg8Q5OCv1bKWHFmGwcS6M83e7ZVcCwYDF3tLjYySg6W5EhWuLvstNXseSCQIud/kgq8ROFdUTRsFge646Cwtp+5KFcJYm3DoKvM0PmY28QOzH6i/yVXgqpmq8RqMgyRf5HW8AB0+J1U4qUSivyAvdnlGYm98pNvkg74TRST0TZ5jcl9x1vmKSr4RXy9gIHd1pmbYWtplJ/8AFJBv+NMPLKSNrH2+9aNdNA0rhxSZ48DjY7X8O99d7lJJBlaPG4xhX2eVos5ha072Jcb/AFQaCgD4YIXHK4Od9nN/EdSR8bfJJJBveLsMkkwpsrXXBZAdz5IZw3HOcPLQ46NmB73qfqkkg4+ziGoL6gAnaO/e9Vxp6ecYvub9vJ7/AJFJJBL2gU07KinkzG4YCDm6OJVvj2Gd0EDnOOkhHi6j+kkkEqimndhN83+GP3jyITcH0sxopBm0zSjxnYtCSSANwHHIZZMz7MBjLzmuANblWZ8bnrqltFGD2WezQdifzO8kkkBPjejmFNTgvuWkDxH8qjV0Upwgku0+ztI7x6hJJBlnUcpwyMh2gf8AmP5iPqtfh1BO/B3d/TsJB4jyJSSQcvZ5BKYJm57WkHvHmP6Q7gWhl+2TtDtMruZ5OSSQFKDAn/8AzOr7DPfr7iEe1enjjrGgEuJYzS++6SSDK8O4tJTfayBlBjde2gvyWu9m9awUc5yF5aZC7z7t0kkGajnke6CUizTORoNLBtvqUkkkH//Z" alt="user">
                                </a>
        
                            </div>
                            
        
                            <div class="profile-info">
    
                                <span class="profile-link">
                                    <a href="#">fagbs_id</a>
                                </span>
                               
                                <span class="time-stamp">
                                    15 HOURS AGO
                                </span>
                            </div>
    
                        </div>

                        <div class="story">
                            
                            
                            <div class="profile-pic">
    
                                <a href="#">
                                    <img class="picture" src="https://mir-s3-cdn-cf.behance.net/user/276/a217775903389.550d7721899d8.jpg" alt="user">
                                </a>
        
                            </div>
                            
        
                            <div class="profile-info">
    
                                <span class="profile-link">
                                    <a href="#">adekunleosilaja</a>
                                </span>
                               
                                <span class="time-stamp">
                                    3 HOURS AGO
                                </span>
                            </div>
    
                        </div>

                        <div class="story">
                            
                            
                            <div class="profile-pic">
    
                                <a href="#">
                                    <img class="picture" src="https://is5-ssl.mzstatic.com/image/thumb/Music113/v4/74/f2/c2/74f2c2b7-842d-3af6-1ba2-d4563b897c8f/pr_source.png/800x800bb.jpeg" alt="user">
                                </a>
        
                            </div>
                            
        
                            <div class="profile-info">
    
                                <span class="profile-link">
                                    <a href="#">iamjodeep</a>
                                </span>
                               
                                <span class="time-stamp">
                                    7 HOURS AGO
                                </span>
                            </div>
    
                        </div>

                        <div class="story">
                            
                            
                            <div class="profile-pic">
    
                                <a href="#">
                                    <img class="picture" src="https://dailypost.ng/wp-content/uploads/2019/06/Biodun-fatoyinbo.jpg" alt="user">
                                </a>
        
                            </div>
                            
        
                            <div class="profile-info">
    
                                <span class="profile-link">
                                    <a href="#">biodunfatoyinbo</a>
                                </span>
                               
                                <span class="time-stamp">
                                    23 HOURS AGO
                                </span>
                            </div>
    
                        </div>

                        <div class="story">
                            
                            
                            <div class="profile-pic">
    
                                <a href="#">
                                    <img class="picture" src="data:image/jpeg;base64,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" alt="user">
                                </a>
        
                            </div>
                            
        
                            <div class="profile-info">
    
                                <span class="profile-link">
                                    <a href="#">jjhairston</a>
                                </span>
                               
                                <span class="time-stamp">
                                    2 HOURS AGO
                                </span>
                            </div>
    
                        </div>


                    </div>

                </div>

                <div class="aside3">

                    <div class="aside3-t">

                        <div class="aside2-top">

                            <div class="aside2-top1 tp3">
                                Suggestions For All
                            </div>
    
                            <div class="aside2-top2">
                                <a href="#">See All</a>
                            </div>

                        </div>

                        <div class="aside3-body">

                            <div class="st">

                                <div class="suggestions">

                                    <div class="sugg-pix">

                                        <a href="#">
                                            <img class="picture" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/12/User_icon_2.svg/1024px-User_icon_2.svg.png" alt="user">
                                        </a>
                
                                    </div>

                                    <div class="profile-info">
    
                                        <span class="profile-link s-link">
                                            <a href="#">officiallee</a>
                                        </span>
                                    
                                        <span class="time-stamp">
                                            New to Instagram
                                        </span>
                                    </div>

                                     
                                    <button class="follow">
                                        <a href="#" class="ff">Follow</a>
                                    </button>

                                </div> 

                                <div class="suggestions">

                                    <div class="sugg-pix">

                                        <a href="#">
                                            <img class="picture" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/12/User_icon_2.svg/1024px-User_icon_2.svg.png" alt="user">
                                        </a>
                
                                    </div>

                                    <div class="profile-info">
    
                                        <span class="profile-link s-link">
                                            <a href="#">officiallee</a>
                                        </span>
                                    
                                        <span class="time-stamp">
                                            New to Instagram
                                        </span>
                                    </div>

                                     
                                    <button class="follow">
                                        <a href="#" class="ff">Follow</a>
                                    </button>

                                </div>     
                               
                                <div class="suggestions">

                                    <div class="sugg-pix">

                                        <a href="#">
                                            <img class="picture" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/12/User_icon_2.svg/1024px-User_icon_2.svg.png" alt="user">
                                        </a>
                
                                    </div>

                                    <div class="profile-info">
    
                                        <span class="profile-link s-link">
                                            <a href="#">officiallee</a>
                                        </span>
                                    
                                        <span class="time-stamp">
                                            New to Instagram
                                        </span>
                                    </div>

                                     
                                    <button class="follow">
                                        <a href="#" class="ff">Follow</a>
                                    </button>

                                </div> 

                            </div>
    
    
                        </div>


                    </div>
        

 

                </div>
    
                
            </div>
           

            </div>
        </div>
    </body>
</html>
 
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Roboto', sans-serif;
    font-size: 10px;
}

        /* Page top */

.top {
   
    background-color: #fff;
    border-bottom: 1px solid #dbdbdb;
    height: 77px;
    position: relative;
    top: 0;
    width: 100%;
    z-index: 1;
    position: fixed;
}
.top-items {
    display: flex;
    height: 77px;
    max-width: 975px;
    padding: 26px 20px;
    justify-content: space-evenly;
    width: 100%;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

.logo-area {
    display: flex; 
    flex: 1 9999 0%;
    min-width: 40px;
    justify-content: flex-start;
    flex-direction: row;
    align-content: stretch;
 
}

.search-box {
    position: absolute;
    top: 35%;
    left: 40%;
    transform: translate(-50%, -50%);
}

.search {
    border: 1px solid rgba(196, 196, 196, 0.418);
    border-radius: 3px;
    width: 200px;
    color: #999;
    cursor: text;
    font-size: 14px;
    font-weight: 300;
    left: 0;
    padding: 7px;
    position: absolute;
    text-align: center;
    top: 0;
}
.search-box:hover {
    transform: translateY(-2px);
    box-shadow: 1px 3px 1px rgb(53, 52, 52);
}
.search-box:active {
    transform: scaleX(1.04);
}
.ic {
    left: 55px;
    opacity: 0.5;
    position: relative;
    top: 12px;
    background-repeat: no-repeat;
    background-position: -387px -337px;
    height: 10px;
    width: 10px;
}

.sb {
    position: absolute;
}

.acct-actions {
    display: flex;
    justify-content: flex-end;
    flex-direction: row;
    position: absolute;
    top: 35%;
    left: 70%;
    white-space: nowrap;
}

.actions {
    display: flex;
    flex-direction: row;
    padding-left: 24px;
    white-space: nowrap;
}

.li {
    height: 24px;
    margin-right: 25px;
    opacity: 0.8;
}

                /* Statuses */
.statuses {
    height: 120px;
    outline: 0;
    background: #fafafa;
    border-bottom: 1px solid #dbdbdb;
    display: block;
    padding: 10px 0;
}
.full {
    display: none;
}
.status {
    flex-direction: row;
    padding-left: 8px;
    padding-right: 8px;
    height: 120px;
}
.status-ride {
    display: flex;
    padding-left: 0px;
    padding-right: 8880px;
}
.status_ {
    height: 122px;
    padding: 0 16px;
    width: 80px;
}
.status-pix {
    border: 3px solid rgb(190, 76, 47);
    height: 66px;
    width: 66px;
    border-radius: 50%;
}
.pix {
    height: 60px;
    width: 60px;
    border-radius: 50%;
}

                /* page body */

.main {
    /* background-color: rgb(240, 240, 240); */
    width: 100%;
    height: 2300px;
    background: #fafafa;
}

.section {
    justify-content: space-between;
    margin-left: 13.5%;
    background: #fff;
    width: 47%;
    height: 700px;
    border-radius: 4px;
    display: block;
    float: left;
}

.section2 {
    margin-top: 60px;
    height: 715px;
}

.top-section {
    background: #fff;
    display: flex;
    justify-content: space-between;
    height: 60px;
    padding: 16px;
    width: 100%;
    border-bottom: 1px solid #efefef;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
}

.section-title {
    display: flex;
}

.profile-pic {
    border: 3px solid rgb(190, 76, 47);
    height: 40px;
    width: 40px;
    border-radius: 50%;
}

.picture {
    height: 34px;
    width: 34px;
    border-radius: 50%;
}

.options {
    display: flex;
    flex-direction: row;
}

.opt {
    margin-top: 2%;
}
.profile {
    margin: 10px 15px;
}
.profile_tag {
    font-size: 1.4rem;
}
.profile a {
    text-decoration: none;
    color: #262626;
}
.op {
    height: 3px;
    width: 3px;
    margin: 1px;
    background-color: #262626;
    border-radius: 50%;
}


.upload {
    background-size: cover;
    height: 400px;
    width: 100%;
    background: #fff;
    display: flex;
    justify-content: center;
}

.upload-content {
    width: 100%;
    height: 100%;
}

.upload-actions {
    display: flex;
    height: 40px;
    padding: 0px 16px;
    margin: 4px 0px 0px;
}
.u-actions-li {
    height: 40px;
    width: 40px;
    padding-right: 4px;
    height: 24px;
    border: 0px;
    background: 0;
    padding-right: 8px;
}
.aside-tag {
    width: 80%;
    align-content: flex-end;
    display: block;
    padding: 0;
}
.tag {
   float: right;
}
.liked {
    margin: 0px 0px 8px;
    padding: 0px 16px;
    font-size: 1.4rem;
}
.liked-count {
    font-size: 1.4rem;
}
.likes {
    font-weight: 650;
    text-decoration: none;
    color: #262626;
    font-size: 1.4rem;
}
.others {
    font-weight: 650;
    text-decoration: none;
    color: #262626;
    border: 0px;
    background: 0;
    font-size: 1.4rem;
}
.upload-caption {
    padding: 0px 16px;
    margin-bottom: 4px;
}
.post {
    font-size: 1.4rem;
}

.post-link {
    font-size: 1.4rem;
    color: #262626;
}

.comments {
    display: block;
    padding: 0px 16px;
    margin-bottom: 6px;
}
.comment {
    padding-right: 6px;
    opacity: 0.5;
}
.like {
    float: right;
}
.push{
    padding-left: 50px;
}
.submit {
    border-top: 1px solid #efefef;
    color: #999;
    font-size: 14px;
    line-height: 18px;
    min-height: 56px;
    justify-content: center;
    margin-top: 4px;
}
.ssub {
    align-items: center;
    display: flex;
    flex-direction: row;
    flex-grow: 1;
    flex-shrink: 1;
    position: relative;
    padding: 0px 16px; 
    margin: 4px 0px 0px;
}
.texta {
    background: 0 0;
    border: 0;
    color: #262626;
    display: flex;
    flex-grow: 1;
    font-size: 1.4rem;
    height: 18px;
    max-height: 80px;
    outline: 0;
    padding: 0;
    resize: none;
}
.button {
    opacity: .3;
    pointer-events: none;
    border: 0;
    color: #3897f0;
    display: inline;
    padding: 0;
    position: relative;
}
/* Aside section pc screen alone */

.aside-section {
    display: flex;
    flex-direction: column;
    height: 850px;
    padding-left: 1%;
    /* padding: 0; */
    right: 0;
    width: 30%;
}

.aside1 {
    height: 62px;
    margin-bottom: 10px;
    padding: 0;
    right: 0;
    width: 90%;
}

.user-profile {
    align-items: center;
    display: flex;
    flex-direction: row;
    height: 100%;
    margin-bottom: 12px;
    max-height: 50px;
    width: 100%;
    padding-left: 5px;
}

.own-profile-pic {
    border-radius: 50%;
    margin-top: 5%;
}

.own-picture {
    height: 50px;
    width: 50px;
    border-radius: 50%;
}

.own-account {
    display: flex;
    flex-direction: column;
}

.user {
    margin-top: 20px;
    margin-left: 20px;
}
.user a {
    text-decoration: none;
    color: #3b3b3b;
}

.identity {
    font-weight: 600;
    font-size: 1.2rem;
}

.username {
    margin-top: 2%;
    opacity: 0.8;
    font-size: .8rem;
    font-size: 1.2rem;
}

.follow {
    height: 50px;
    width: 50px;
    align-content: flex-end;
}
.upload-actions {
    padding-left: 16px;
    padding-right: 16px;
    padding-top: 4px;
}

/* Aside 2: Stories */


.aside2 {
    width: 80%;
    background-color: #fff;
    border: 1px solid #dbdbdb;
    border-radius: 4px;
    height: 190px;  
}


.aside2-top {
    display: flex;
    justify-content: space-between;
    padding-top: 2%;
}

.aside2-top1 {
    width: 70%;
    padding: 2%;
    color: #3b3b3b;
    font-size: 1.2rem;
}
.aside2-top2 {
    margin: 2%;
    padding-right: 5px;
}

.aside2-top2 a {
    font-size: 14px;
    font-weight: 650;
    text-decoration: none;
    color: #262626;
}
.aside2-body {
    height: 150px;
    overflow: auto;
    overflow-x: hidden;
}

.story {
    display: flex;
    margin-top: 4px;
    margin-left: 2%;
    height: 50px;
    width: 100%;
    padding-top: 4px;
}
.profile-info {
    display: flex;
    flex-direction: column;
}


.profile-link {
    padding: 5%; 
    margin-left: 2%;
    font-weight: 500;
    
}

.profile-link a {

    text-decoration: none;
    color: #262626;
    font-size: 1.5rem;
}
.time-stamp {
    margin-left: 4px;
    opacity: 0.7;
}

.aside3 {
    margin-top: 2%;
    width: 80%;
    background-color: #fff;
    border: 1px solid #dbdbdb;
    border-radius: 4px;
    height: 220px;
}

.tp3 {
    width: 70%;
}

.aside3-t {
    padding: 5px;
}

.suggestions {
    display: flex;
    padding: 3px;
}
.see-all {
    padding-right: 2%;
}
.st {
    margin-top: 4px;
    margin-left: 2%;
    height: 50px;
    width: 100%;
    padding-top: 4px;
}
.sugg-pix {
    margin-top: 5px;
    height: 40px;
    width: 40px;
    padding-right: 5px;
}

.follow {
    position: relative;
    justify-content: center;
    top: 40%;
    left: 35%;
    border: hidden;
    background: white;
}

.follow a {
    text-decoration: none;
   
}

.ff {
    font-size: 1.2rem;
    color: rgb(40, 94, 212);
}

/* Media Queries */

/*
Media Queries Max-widths
    Tablets = 768px;
    Phones  = 408px; 
*/  

/* iPad Pro */


@media (max-width: 1024px) {

    .top {
        height: 54px;
        padding: 0 10px;
    }

    .aside2-top2 {
        width: 20%;
    }

    .aside2-top2 a {
        font-size: .8rem;
    }

    .follow {
        left: 15%;
    }

    .push3 {
        padding-left: -50px
    }
}


/* tab Screen */

@media (max-width: 768px) { 
    .top {
        height: 54px;
        padding: 0 20px;
        position: sticky;
    }

    .statuses {
        height: 120px;
        outline: 0;
        justify-content: space-between;
        margin-left: 13.5%;
        border: 1px solid #dbdbdb;
        display: block;
        padding: 10px;
        overflow-y: hidden;
        width: 600px;
        overflow: auto hidden;
        border-radius: 3px;
        margin-bottom: 24px;
    }

    .section {
        justify-content: space-between;
        margin-left: 13.5%;
        background: #fff;
        width: 600px;
        height: 700px;
        border-radius: 4px;
    }

    .aside-section {
        display: none;
    }

    .main {
        height: 2400px;
    }

    .push2 {
        padding-top: 40%;
    }
        
}




/* Phone Screen */

@media (max-width: 414px) {
    .search-box, .sb{
        display: none;
    }
    /* .statuses {
        padding-top: 10%;
    } */
    .main {
        height: 2200px;
    }
    .top {
        height: 54px;
        padding: 0 20px;
        max-width: 411px;
        position: sticky;
    }
    .top-items {
        width: 100%;
    }
    .acct-actions {
        left: 50%;
    }
   .actions {
        width: 185px;
   }
   .statuses {
    margin: 0;
    width: auto;
    border: 0;
    border-bottom: 1px solid #dbdbdb;
    padding-left: 0;
}

.section {
    margin: 0;
    background: #fafafa;
    width: 100%;
}


.top-section {
    background: #fafafa;
}

.section2 {
    margin-top: 50px;
}
.comment {
    display: none;
}
.submit {
    display: none;
}

.upload-caption {
    width: 90%;
    margin-left: 4%;
}


.u-actions-li {
    padding-right: 0;
}

.like {
    margin-top: -15px;
}
.push2 {
    padding-left: 50px;
}

}
