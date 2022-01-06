# List of All Competitive Programming Contest List

## Table of Contents :clipboard:
1.  [Testing-Team-Data](#1-Testing-Team)
     - [API-Automation](#11-API-Automation)
        - [Dashbord-Link](#111-Dashbord-Link)
        - [GMP-QA](#112-GMP-QA)
        - [GMP-Staging](#113-GMP-Staging)
        - [GMP-Production](#114-GMP-Production)
        - [Apcoa-QA](#115-Apcoa-QA)
        - [Apcoa-Staging ](#116-Apcoa-Staging)
        - [Apcao-Production](#117-Apcao-Production)
        - [Elite-Production](#118-Elite-Production)
        - [One-Parking-Production](#119-One-Parking-Production)
        - [Drop-Down](#119.0-Drop-Down)
        - [Table](#119.1-Table)

2.  [BAckend-Team-Data](#2-Backend-Team-Data)

# 1 Testing-Team

- ## 1.1 API-Automation
  - ### 1.1.1 Dashbord-Link
      Name |Link | login-id| login-pass | card details
      --- | --- | --- | --- | -----------
      apcoa-staging-admin | https://dashboard.flow-connect.net/login | dashboard_user | Gmp1234! | 
      apcoa-qa-consumer | https://apcoa-qa.dr7mhrdui99du.amplifyapp.com/app | | | Card 
      apcoa-prod-consumer | https://dh4ol850ajlmv.cloudfront.net/app | | | Cardno-4111111111111111 exp date-any
      gmp-qa-admin|https://gmpone-admin-db.getmyparking.com/admin/permit | dashboard_user | dashboard_user | 
      gmp-qa-consumer|https://global-qa-copy1.di8ln77nkrd5v.amplifyapp.com/app/v2 | | |  Card no-4111111111111111 exp date-any
      gmp-staging-admin|https://gmptwo-admin-staging.getmyparking.com/ | dashboard_user | dashboard_user | 
      gmp-staging-consumer|https://stagingpermit-three.getmyparking.com/app/v2 | | |  Card no-4111111111111111 exp date-any
      gmp-prod-admin | https://portal.getmyparking.com/login | richa/sudeshna  | GMPgmp@02
      gmp-prod-consumer | https://permit.getmyparking.com/app |gmp.prod.testing@yopmail.com | testing| Card no-4111111111111111 exp date-any
      elite-production-admin|https://dashboard.elitevipallaccess.com/login |dashboard_user |02tvzzD6p25n@ |
      elite-prod-consumer | https://consumer.elitevipallaccess.com/app | | | Card no-4111111111111111 exp date-any
      one-parking-production-admin|https://oneparking.getmyparking.com/login |dashboard_user |GMP@1234 |
      one-parking-prod-consumer | https://oneparkingpermit.getmyparking.com | | | 



  - ### 1.1.2 GMP-QA :heavy_check_mark:
    - <details>
        <summary>Parking Details</summary>
          
          BASE_URL = "https://qa.getmyparking.com"
          HMAC_USERNAME = "qa_tester_hmac"
          HMAC_PASSWORD = "SNMSpsRbfbz4VoHFVjD51cJFL61bVllK"
          
          ### for india
          login_pass="testing"
          login_email="amit.gmp.qa2@yopmail.com"
          consumer_userid=104811
          consumer_paymentid=4814
          LOCATION_ID = "ENABLEGMP07"  
          ID = "AMIT1234"  
          ENTRY_LANE_ID = 69  
          EXIT_LANE_ID = 70
          PassMasterID=130     
          ## for pass creation :: note these details can be fetched from admin Dashbord
          ## by default pass valid for 1 hour
          parkingDetails= {                                
                "id": 35,                                  
                "name": "GMP [enable working]",           
                "address": "Sector 6, HSR Layout"         
          }
    - <details>
        <summary>cURL</summary>
    
    - <details>
        <summary>admin dashbord login bearer</summary>
          Bearer eyJhbGciOiJIUzI1NiIsInppcCI6IkdaSVAifQ.H4sIAAAAAAAAAO1dW2-jOBj9Kyue-7DtNt3dvrngRNYARmC6qkYjxLSoE02boJCutqrmv6-5JG1CqQqxHX_AwyhTLhacfj0-3zUvRvb03bg07uLsx_dlvLqLnrJkZZwY8yzjh-8fU5omq3i9XAXr-H6-uOeniisuX4xF_Jjwa2aO91tY3rSsriV3xuXf5YXVRbX1848gybL5csGe0_wSJ7QZebOIl6we58UF_Em-vhhzvuji6eHh43XT7V38LDJNGrosmvk09HZOWvMsfYif3WKVctXXk7PV8il9eyq-veWPaif_Jg98VYZd5DJj53D-xqcnxjpZxIv15rb6m6DbdfFkX43QsxDDfBEfI4t_mPyT__ztxLhdPqbxYvfR4tVPjv07h-zl-u3R6l5yt3dZ7QC_b3Ps10knbE3qBqGD_SjAQUCoKwxekzoecm_q-J6ftQG4wnWLs4VtXPwHHNIOctEMRxvA5QN9ehDQFb5bxOEAvTXpMMjtOvQ86jMFdv17B7i3KFe4w0GZethHjJYoK0C3FS03oAvQmC18TUwcWZghYgeabn5bUga_Cwo1Zg_5X4g7q6N8MWkBMxwU5eg0QfvblgsqG93aLDjmZcgn06leVNAfdJXLtHY72z7Q4PA1kZ_zYuRQK7SxXla8v4_ti2E4KHsoCERDLFebwcHWQcSNbBKI8ymEGO_owB2qyi46EfFuCAgoyqPm7Uq02HcIi0rV4GBXM1JoiE8CJAVkOURFdFIE58JBVbAvMcJaBcemU06sqvRXO0e4LhB2fTY4KEuKjYk14n1PGKA1S3LZJAV2wPkTYnc2Kb4E3Kybj6-xG-LIxzKciMim70Hdyn73sYXrURRBB8FAj0GHDbalwYlO0zf6a2enfw6Khek19q8J_kfDyE7PGIL_IzM395UjRiOT-pwwyrcZMQcT5xGbNaqLZGAgF4Zt-qGlFcDA8JOj0Q7VZ-Clw64Ejq5uIkYcfd04-FwgLSQsttSvEXE4UKuNs50NNM52pIJKIfWrcFAuwkC6yuHGSkpw7Kw67dkqqdzAGXDQlRWmkNRNAI4klOXrhiWRpXXBiIzG90CvlfEf26amyB1OkKMHPoQJoU8OvBj2sYmJx_ICYaZvuU-dK4AJCY7GlV2UYU_JTC-Q9xP7cLc91T1cIkQFQMpQ31IgIlABB9-SK7SFFXxTnDJnToheA0gQ4rNHY9mExADxKNXgBC77I9Y2MG_-sLUiCvC-cz1J6qGbokaFk4duyVLIsNqURezG0w3SphkGAE1Zdbn2wJhCoVg7azVSBnyl2l7yKJpSUzfr7Q9LKHOah8UOCja85nTHMDtDJbV4jMVWTfEgNZUTf7RpGO9Tt92RxtcNq0P3SDMm2hl1f2pi5XTXyK0KArgVyqmvGHs9FOyD4-TLPZj5c6PICh3NKln6MyNM8bjGdpzcH5iVd-62KzkGj6_ycGeXOc9w4VUY7uw4xwZqfYVqTSwiEAdQR6iWa63ooUEMA7TmIznULcdUgId5xh83-pK3l1KXMOqXoGhFHcDcOTmVxmNnzZHU74FtjVDbElRb8bCixYUInvrUiSzdAmtwQFQtxAbara909HvHim3wXeQy5tUMiw2Ud4q3m94BvhBFfSf-sCSBpKqT8dt4dmNkSgf8dJQM9eYCYLuZ4FrAJhs-7xAZgwMityondImJWF67qmPjchHFhwSoUn_h0KnNUIWC8vzZsCb2vNdY9HZ2uFZW3Z8qykbYNYtAjv2J44yDT7E0MaluPtyYTDtalQPAuKRiV26gVZNl9BcFTD_JDD6XqbpgZ6CVJFUqkzIVRakDnWKn2ulrF3wH7_Sp_frlYZVNqh9L1bFysqGEHQ7SihsEOibowMOceyG5E2IRNHNpwIi4qQdiJ1WBz3Oo-g7hA4sigKEqZ4qopKZDqCRxrK7wYWkLAAEhYORwBLXWbWgS-D6XMv4ehFe6jmLsT0vnkchYyPdPwUFZdX_yYMcZVGwRaRw71kgkf3t9UvT6Shl_ypcPQf9s9_Yk_z1-fqEPAG63UCPH5288z-z5OvGTdLlab6ytWJs9p_naG0T47cl_Kb_p4vx0cv7X2WTy638HhGXUnJwAAA.6xXHrB9-j1kWoneNj-7bDCnn1kKPDHiEtG2bFM-HYm0
    </details>
  - ### 1.1.3 GMP-Staging :heavy_check_mark:
    - <details>
        <summary>Parking Details</summary>
          
          BASE_URL = "https://staging.parkingplusmore.com"
          HMAC_USERNAME = "apcoa"
          HMAC_PASSWORD = "zQUC/hng9WkG4XJMwyKwde4aeTsF3BNijcWHESVzevs="
          
          ### for Canada
          login_pass="testing"
          login_email="apiautomationstaging@yopmail.com"
          consumer_userid=4993
          consumer_paymentid=2162
          LOCATION_ID = "ENABLEGMP112"  
          ID = "STAGING10"  
          ENTRY_LANE_ID = 244  
          EXIT_LANE_ID =245
          PassMasterID=103  
          ## for pass creation :: note these details can be fetched from admin Dashbord
          ## by default pass valid for 1 month
          parkingDetails= {                                
                "id":2996,                                  
                "name": "Raj New Test (enable working)",       
                "address": "wwfwef"         
          } 
    </details>

    - <details>
        <summary>admin dashbord login bearer</summary>
          Bearer eyJhbGciOiJIUzI1NiIsInppcCI6IkdaSVAifQ.H4sIAAAAAAAAAO1dXW_aShD9K1c856EkaRL65pold1UbI39QRVVl0QT1opsAAnJ1q-j-92sD-QBi1F2vZ_d4_dQIjGtOJrMzZ2bOPLWWjz9an1p3o-VfP2ajxV36uBwvWietyXKZvfzzYR7Mx4vRaraIVqOfk-nP7K31FZ-eWtPRwzi7pvv80T-SzUdn20_wu9ani_PN9dtrD_6b_J9ovFxOZtP41zy_xE-8mL-5y2C8eJisL8ge6NtTa5Lddfp4f3_8vvOXT2XvhmzI-glLQzYIwjj9fJPG3Gc7V3Uny_n96Fd_fbvN7V_fvF7MHudv3xrd3mbP7I3_Gd9nt3cDf-D0b1o7r-dfPvvuq_F0NF09f-7wOzm3q_Uzfvt-0rqdPcxH091nGC3-zkB_5yVvtnr76vaz_G7vsoMXss89v_bfiRSaAyf8wvvXacSiiAd9ZTBu73sI4-nV2aUAktmv2-m2cPB0g36U-CxUDmjM-k4_fgdPETDdDM04_1t5-aHLPLb-YY3zSSsZdPM3cADfM-C0F7jV-4LLMynUt-Duo44D9qHvff07r9pvdNr19MDcd65ZOmQh73HXiVX6jEL7vRCB8tVstz5ia884EPtOP8f42TcT-AchfHddLyC-77mFG5_149QPugShmYg3xkE1GLDQiYMwTSISm72QsNnCow0I5sz1Djn7mno8ik2DuT5xmuuE-dmee4TEI_AJkjjvnnU48Dpdn_fTVzSMQrfAWYCha1pYhm-zrhskWZBwHQbJgMBmP0rY7IvfxY3OqqJ41AKN6xxY3_nssTSIKWxYiHjYt9mTPavGwZg6SBOy4Bcf0Xjkd2E-wgV35Ox532fA2fPAiSK6UFjImvdB3rduHJCJ4wux6G2f9MGFOfsCTtpNfHUQK6l1gLleeo5SJoWrQTgcOyHv9UzDF55jp88y5AgeVP4sJ4G3BLtpaQZ8_WLAQp_H6cYF53UL06y3Pt6XNPCVCcgOGXc4V6GzSn_VFjFsHEzp-6Q6naaC0RxxSv1uLwz8dPsNDMrUCkwXkNahpinl2tAKqAccmKs_4GzrAqYPgGVis7rEv2RpnEwhDhfbLhtyl6VdFjvci5ozrj79qpJlT1QurSJDVlS5OCx3onJqLncD04wX3gvrINPk-qYOwwmwlJm8p1JubGDXT-DAG_0ZfE3zlC6KnaanUjW6iutwUfI5dYMwC6w3eOyB2-6oCNdw0D1Mkb0gTuObQTOOoQRRs1BEs85Ny6RZGRoYhJUNGqs-_fcnV-ACWvIoS65dDzXKus6eOv2SZwxBn8dBaByNiwboi2dYt4xEyYCIbJQJX4HT3AqIXLVMI_zIoMYyjxRng5uLae0YEWIfcTAl6zMt1eUEZ6r0cW8909mKGkIKUTxt2zkdASYvgMp3bYcwM-_Q4-pOLSUB2WGGhir_RE2Il1TZAkNXj5KZXVkbkZCDZagSn3GSMhnwZxzpCJBlWiQauQahyLgGiOaVyCZrg_C0JR0tKvE4dOhm1CR77-B7HKnFn4RyiQILBoRZOQt5pMNGiOGBN2Ddoqf1ZM2pRU9L6mmhMjkaZP_FpJ7g6xR0jvf0QmihAnzXPlVhTUrPCddgqQtCkoEvfERWUTuZklJF4YAl3AFHVn0XataDp8noVZ5UjLgj4UvrhCXTYnicGzX6arO4Xo-Fpo-lFVgzDso6Z3wsa5AkpiVsjY2pNaBsC94oRadLyXPiiu9pmr6wa-GYhuG3kgEcKlFMHMmVyvZwnQYxynIDhviDnG9ds3klD_iKKFFzpV0iJPR7ASylhDa5x76MiEHkfH30OzVIREm2s7phsgM1mPMImcv4IM69R2ygrD28z9DdA2TZhEwFfZmKPHOCBKMWxQ2JbgocROn5iJoODZBHu6VkqHHrGZQd7krEewGjXOJihl3zWtVwOc1ux6MBrmm-Aj5_QJLqwj3syI3Ysulv4pGNUpvzcK2YdnOIXf1qpNhKUpGoZxz1oKfc2l344qbjxnzI47wH0DD9o4Yds1uPNuj1PN43NYcAA5M471USygJyN9QwC3XkFAazcHEX0QImuX4n2EhgyzuqbmJQu2awBhlZNZqTTU72xozNimThmTDSCYCLks0JqC3TtESNXY3_lHJGMq4BF1m8kYrdQAIHacU2rFajGp4Ho9Zbt3SPOXFzgxhnDt_0T7wb80PJOVjoSM3xvMA1UGyjTmJzlAFxSZDhsNWwNMBS_fUXF5pu8mgniinI4XKbc-AiC8264Y2wSRMuq4eZfopTrqIEb8_0NIYSmVBAGqPLhtxlaZfFDvci0xxzfZIUDcScnO-Aj6WbjZ3IRX45hgiV5qTuqlSBLuAhR6niLtNFgRsRa1053RbBGgfTapI5tcri8IZLLoFt2cHWiEjhRwtyMxgFen44MFdVTyqu3AltfsHPJKhV2-2qJRHoidsXk2ka8ZZsmECNGsj3ZliqG2N0yzv--UY8dVRqywAuzPRh2lUtjzbSaQI5W4Wfnqd2CTLdDzWY9yRiHSybRCRuY5VcQI2arhEvDZCb1ijgfXFQpl5JpII6w0OXblZZRUYBeMBp6l21q5mSmGa3VJPSaAmUOtU5aYdjShGWuNa8hnm7ZsKgen1B5w6gU9awbESJii1gkIGybgR1AIm8yqFimwugHWtwGZYOEZA3U0nm16gMXDWxstp1ZvCCHsQzdKVcBW4cRz5CV24JOy6LoWspgYrSEw7K1Ol1SfoeNWQmXXRkKcZVpX3N4MEOzFqEyWstpk0_lV-KS8YNKQwv8zXzikQMJ-oJR09TWDafRNxkYZdoLnFZWjJvhm_VpOohtGt9FHnNw1ItTNpuQlv3qVYVCKtNleHjNeqNnyLWjIMirUuwNGqoyFTVqsIfcpWomcbhjHPM_WaUHNt12FqpM7e4UR9RwGr2SajtoICvIJFOktq6QJyMG1axMxQHVt_JMjrjnAMOfrraTUryPGgeVkMXfKnuYdxGNdJ1J1LLIXDPMGr9Gdt60ojLnKdC-nXwXI-uo86ucidYZyWsMZPIuttluoTrbcVcb300Wk0e1qhPHxrtyj_bpkCridKOaLOeiQjY4eFp8lRtfXxCtdHvEevtqBjHx8HZ7AUF8PCaLLtWn53BVM2UKhQOcFDVsEvO0p3Xug67zpVQqAZfntdR15CrHMHXNbbcexAbN0NQ2BgMZ87a3EbHLl0UYo5YrEpXMEsACDPBRhnLerINZN3ho2Li-bizkj3YqMw79_Nh-yELeY9nbtc8agK-O4J4jNauGeXChbX5mWYW2Digkjb-Wj10aBrVA1-rJ6fZxcy3BmVOypkAFXomWmOy76-P7Lx-t2X2uE9HMf-91vP2h_y3-Pv3KQS6fSl2o8JeeEXPc54DN1l6k9U4HM9ni9Wzza5vHv-a5zd_Bjb7-PjfefYlLs7bH8-vLs9P__sfx69fpXNBAQA.BqwO9JfOA9NfSzSca4II5jaCPSo85-P6zUsax_4x5yg
    </details>
  - ### 1.1.4 GMP-Production
    - <details>
        <summary>Parking Details</summary>
          
          BASE_URL = "https://qa.getmyparking.com"
          HMAC_USERNAME = "qa_tester_hmac"
          HMAC_PASSWORD = "SNMSpsRbfbz4VoHFVjD51cJFL61bVllK"

          ### for india
          login_pass="testing"
          login_email="amit.gmp.qa2@yopmail.com"
          consumer_userid=104811
          consumer_paymentid=4814
          LOCATION_ID = "ENABLEGMP07"  
          ID = "AMIT1234"  
          ENTRY_LANE_ID = 69  
          EXIT_LANE_ID = 70
          PassMasterID=130     
          ## for pass creation :: note these details can be fetched from admin Dashbord
          parkingDetails= {                                
                "id": 35,                                  
                "name": "GMP [enable working]",           
                "address": "Sector 6, HSR Layout"         
          } 
    </details>
  - ### 1.1.5 Apcoa-QA
    - <details>
        <summary>Parking Details</summary>
          
          BASE_URL = "https://staging.parkingplusmore.com"
          HMAC_USERNAME = "apcoa"
          HMAC_PASSWORD = "zQUC/hng9WkG4XJMwyKwde4aeTsF3BNijcWHESVzevs="
          
          ### for Canada
          login_pass="-1"
          login_email="-1"
          consumer_userid=-1
          consumer_paymentid=-1
          LOCATION_ID = "ENABLEGMP112"  
          ID = "-1"  
          ENTRY_LANE_ID = 244  
          EXIT_LANE_ID =245
          PassMasterID=-1     
          ## for pass creation :: note these details can be fetched from admin Dashbord
          parkingDetails= {                                
                "id": -1,                                  
                "name": "Raj New Test (enable working)",       
                "address": "-1"         
          } 
    </details>
  - ### 1.1.6 Apcoa-Staging :heavy_check_mark:
    - <details>
        <summary>Parking Details</summary>
          
          BASE_URL = "https://staging.flow-connect.net"
          HMAC_USERNAME = "apcoa"
          HMAC_PASSWORD = "zQUC/hng9WkG4XJMwyKwde4aeTsF3BNijcWHESVzevs="


          ### for Germany DE
          login_pass="testing"
          login_email="germanyqa12@yopmail.com"
          consumer_userid=598279
          consumer_paymentid=43561
          LOCATION_ID = "EN7440"  
          ID = "XSCD"  
          ENTRY_LANE_ID = 63  
          EXIT_LANE_ID = 64
          PassMasterID=17    
          ## for pass creation :: note these details can be fetched from admin Dashbord
          ## by default pass valid for 1 week
          parkingDetails= {
                "id":1274,
                "name": "P4 Stuttgart Airport",
                "address": "germany"
          }
    - <details>
        <summary>admin dashbord login bearer</summary>
          Bearer eyJhbGciOiJIUzI1NiIsInppcCI6IkdaSVAifQ.H4sIAAAAAAAAAO1dW2_iOBT-L3nmAVJYhr6ZxKBoclMuzFSjkcW0qIu2BQR0taNq_vs64dICk-46OLZPnKdWIXHD16PP5_Kd41dj8_LDuDUepps_fyyn6wfyspmtjZYx32zo5cfnVbCarafb5TreTh_ni0f6UX7H7auxmD7P6D324dGUXjfp58v9E86Dcdvp7-7f33vxZ7If8WyzmS8Xyc9VdouXuonzbpVwtn6e5zfQF_r2aszpqouXp6eP110dn6KfWoEfpx6OSBrj6ORDe75ZPU1_-vkqu1XfPhyvly-r9x9N7-_pq7qzv2dPdNUQRZ8df2ycXM--c2_Qbhnb2WK62B6evPwy6H6bv9w3I8LIpotY9GeC6S9paGe_fG8Z98vn1XRx-nbT9V_0v_CbS-5y-_7q_lnn4ey2iwv0ucO1X61S8CLbc3xusFqBFyL_7hLWmxKg2tjF70E9wgwMXfKGSsUod1lQPke1tcMdDrghjjwnIR7y0Rh72E-qB9hkAdiKUkhwnhAtidMwDCJ-kBYSbqdjtjsl2AEuKeyhIDGOYyfgR74fQNw1mQj4iO3p9gYHYuyjoYu5IZvQ9XJ6OQeWjQ72NHvc104tGQ66EohXL4YQ7PNSfuh80oofLBRlaBAvsFNleQIqPQgKKZic3XNKOHIwONOV4D2YPaaYGD47VEK_XA350pkARxPiDdnsM0ENNi4-AtDsajxRjWMSYa5BMV9kLzc3YIbreDSeIBMcOSPHQglPUuCTmARvxIJ3tkEJcOGAmTNCnuRTig8KShJHWoADsKSMJGMJqHF3WeOJTrcMMbTOkIYDsIoBcQGoAFliTF-ffM7ykYHvJEHE0_Xlk4-sl9vAnYg5gwyVJXY1CxKMRq7jK5aTPGL6JXJA14yRZQWpn5BxFKShohgXFIrggCylwMnks4EnC4nFer30URG2sBMmhAKe8Kx08gz1aiCUkmTPXfOmjDnDxbm60n0hxmZ_0G8wrhzjnr4RiXIpIfgmLNqD65pdJgMG71cElCVQEnA2YC5exbk2Aq6XLNyMdeseoK-LiJ16ioXS9VH7CN7nKA0zStzr5EeIjKPZFJdAARWTkOBRHW0ALmaEK0RTDb5NBkK2T6Yfwor3xcFvPKzIhPmI1OqlRxHqk7EVkRqgBbUbgffZhBNGp5ysFWqeJ8IT7Kd4L88mwzsSorts58savPhJKaoSqkCt84sXDvb-qGXQfJD-JIrl0Qq0gdC3OiGm2i3XUQvVJxYNcLvNJkQB76zBEBGD3cqqaQivVKsNB91gNKLMoHSzPXgZvPiZESVnykDd4fJ2L-S6gbV7fRWtGGrS3cMJGqJYMVjBGah40c5VswvAmWk1HNuIdk6D4a8JjnzkkjDCZBgEXGcZNAOmcowTFDmjkVoWXBChAXTFIjxKfZvkdTi-VFxRoxEwhqjGE7OCKAyi3Yrn5U2m-ib4bU58_1a7zabiAZ_NER2tmX2WzDlYZpDUqKxXNue02qbW3laf8WhHU-bNwk3eTA0RBGOFCDxtiN7yymx4kNDce6sk94Y9FCciJnrxSEteRngNOf8n8PUUPkioGus1VKaSyhsfdqiPuCRn4FEUeMRWtzQE_tQB8ZyrcXFDrCOs1zhAGWNu9TLlw7FbbwldhRj5nIjhwixjzhdb5wB4YYQEiHXLS1Raby7G-eaGaSrSZX0fqknbeOJYmNg4QY4bq8XN9fGWxQZ-erWIyzi5RIvy3S6VKchmdVOvivfVSnZoQIVYYt-yXuGd4KzxoFdmNB1ccaDopDyjJ1yAL_TSc8PI9WFkRnetEbFp3v-NrMSZOMkdcQPFju2rT9pBfPmIZVeDg6OMLqOr5NeFKhRwJixnsHi5zAPUbPAEcc9AVDLStnEWmpNK1HB2GcO3Qmk2OKqQdmZJyRnNUHGuqN-Aj4qtTtV8gcn3Mh4d3L1PSkNduQPRoIZ3wkcsappyV7bmCTWJJqEwxzgyvz5p4IYcAIV2XMGF6zvIqyqX9CCghhniExS9q1w02JZcPU3oNTRfaPSmV-ZSQsXD1EuCLe80azYKhs8S4itINI5jctjgY5xPp6JUMfbzIwiSQPlOJPAEIqmHYzBg6lwslKyBw1t8RM3kzYF3OcTjyyJxhYOjUK-YaZsraDCCbKvCDqTU-Kh7sW0FepGuULLQa-SBjDbmmmqFL886SxxPtZxPfWTDu1CZHEhYMWVEDYihiuF1hYOcyx2LCNV2JRwJ00guVXTNwOfUfnfA586jcANlFYHg-UOKNOXKDsVz0KFiL4G79dJVyGmm0QvjYIKjiYO_ENeJFR8Uf36CJRyQ5c1tZIqwwaoHZUxOYeNi8I7Gbl5jnA5VrZSejyiGS8lCp8XrFaSIL9qxJJHh4HgZ7NEgjyR3oWpZzvqcWEc5cujmWc6Ro_wECri5TgmzXPWqM4mnYJZ0PRwcZYwo1-zEa0Q9XvXC4vocypHHFIqCW9A0Dgdcwa0cnStSOwBBbVQS77D8_vZG6O3tN_RtXj-E9v_LybrZ_4vDUjmavNbKTqri917dPqe1MvUdx6_Y5rWW2eeGfHYAAttahZtDZrzzjTvfzqLZarneHughXzv5ucrWPhg3fXz2zyo7t7D7qdfu3rQHv_4FGqpp7eDTAAA.Jc-9G_IswMocLSooMYt76tzzBR8s5p2OCRNM8PKNnPQ
    </details>
  - ### 1.1.7 Apcoa-Production
    - <details>
        <summary>Parking Details</summary>
          
          BASE_URL = "https://api.apcoaflow.com"
          HMAC_USERNAME = "apcoa"
          HMAC_PASSWORD = "gVEx8ELGDBQz7Yyv"
          
          ### for germany on this vechile deicount is added alredy 
          login_passtesting"
          login_email="nikhitade@yopmail.com"
          consumer_userid=535449
          consumer_paymentid=-1
          LOCATION_ID = "EN7440" : updated working and working
          ID = "S BB 578"  : updated working and working
          ENTRY_LANE_ID = 3462  : updated and working
          EXIT_LANE_ID =3463  : updated and working
          PassMasterID=-1     
          ## for pass creation :: note these details can be fetched from admin Dashbord
          parkingDetails= {                                
                "id": -1,                                  
                "name": "-1",       
                "address": "-1"         
          } 
    - <details>
        <summary>admin dashbord login bearer</summary>
          Bearer eyJhbGciOiJIUzI1NiIsInppcCI6IkdaSVAifQ.H4sIAAAAAAAAAO1d227bRhD9Fz4bBZwYTuunrilKXYS3kpQLIwgIxSEMoboQolzUMPLvXV1tSRFQLumz3Nl9iiBRFx5Pzp6ZOTv74lRP35wbZzqfjSbjavT7Y7GcPpejxd_j2eMvD_Opc-GMq0pc8Tgto7JYjJbzhXjuqSoWzs2LMxtNizdv_5OJ1-bby_h35-bjp8vNxUcX_ux7VpelRVWN57PsuVxdHQz9jL_5xLhYTMfrC8Qv-vLijMU3zJ4mk__9FeX-A8SFUewlLIuSfJh6ycGLvXFVTkbP4foDN1_w-uJgMX8q3740engQv9ov_ikm4lPdKIhZeO8cPL-C4rcLZ1nMRrPl7n2nd8Ueluuf9sVJPNYTH-GKfzNPPBjGvc2Dnud74sHXC0fcUTmaHf7Izc3-5Cl_vnz77Pa9_PvRZSdPiPftnvtx0RTwjCW
    </details>
  - ### 1.1.8 Elite-Production
    - <details>
        <summary>Parking Details</summary>
          
          BASE_URL = "https://dashboard.elitevipallaccess.com/login" : working
          HMAC_USERNAME = "apcoa"
          HMAC_PASSWORD = "zQUC/hng9WkG4XJMwyKwde4aeTsF3BNijcWHESVzevs="
          
          ### for Canada
          login_pass="-1"
          login_email="-1"
          consumer_userid=-1
          consumer_paymentid=-1
          LOCATION_ID = "ENABLEGMP112"  
          ID = "-1"  
          ENTRY_LANE_ID = 244  
          EXIT_LANE_ID =245
          PassMasterID=-1     
          ## for pass creation :: note these details can be fetched from admin Dashbord
          parkingDetails= {                                
                "id": -1,                                  
                "name": "Raj New Test (enable working)",       
                "address": "-1"         
          } 
    </details>
  - ### 1.1.9 One-Parking-Production
    - <details>
        <summary>Parking Details</summary>
          
          BASE_URL = "https://oneparking.getmyparking.com/" : working
          HMAC_USERNAME = "apcoa"
          HMAC_PASSWORD = "zQUC/hng9WkG4XJMwyKwde4aeTsF3BNijcWHESVzevs="
          
          ### for Canada
          login_pass="-1"
          login_email="-1"
          consumer_userid=-1
          consumer_paymentid=-1
          LOCATION_ID = "ENABLEGMP112"  
          ID = "-1"  
          ENTRY_LANE_ID = 244  
          EXIT_LANE_ID =245
          PassMasterID=-1     
          ## for pass creation :: note these details can be fetched from admin Dashbord
          parkingDetails= {                                
                "id": -1,                                  
                "name": "Raj New Test (enable working)",       
                "address": "-1"         
          } 
    </details>


  - ### 1.1.9.0 Drop-Down
    
    <!-- code to add dropdown list -->
    - <details>
        <summary>Heading</summary>
            + markdown list 1
                + nested list 1
                + nested list 2
            + markdown list 2
      </details>
  - ### 1.1.9.1 Table
    
    Attempt | #1 | #2 | #3 | #4 | #5 | #6 | #7 | #8 | #9 | #10 | #11
    --- | --- | --- | --- |--- |--- |--- |--- |--- |--- |--- |---
    Seconds | 301 | 283 | 290 | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269
