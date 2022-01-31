# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

``` 
https://maps.googleapis.com/maps/api/directions/json?destination=place_id:ChIJFcsh6Kg1K4gRcXTlUPjURFA&origin=place_id:ChIJGZrUPW6bLIgRGzsv8js4hOc&waypoints=place_id:ChIJ_Wl-QtxdK4gRfirrTwtXiP4%7Cplace_id:ChIJvXiUZdwhK4gR3B8PJg9zeV8%7Cplace_id:ChIJ9WuyfjI2K4gRzy9pQT9GzUs&departure_time=1646160879&mode=driving&traffic_model=optimistic&avoid=highways&units=metric&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE

```

## Next paste the full JSON response to this query here:

```
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJGZrUPW6bLIgRGzsv8js4hOc",
         "types" : [
            "bakery",
            "cafe",
            "establishment",
            "food",
            "point_of_interest",
            "store"
         ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ_Wl-QtxdK4gRfirrTwtXiP4",
         "types" : [ "establishment", "food", "point_of_interest", "store" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJvXiUZdwhK4gR3B8PJg9zeV8",
         "types" : [ "establishment", "food", "point_of_interest", "store" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ9WuyfjI2K4gRzy9pQT9GzUs",
         "types" : [ "establishment", "food", "point_of_interest", "restaurant" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJFcsh6Kg1K4gRcXTlUPjURFA",
         "types" : [ "bakery", "establishment", "food", "point_of_interest", "store" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 43.6396252,
               "lng" : -79.4428415
            },
            "southwest" : {
               "lat" : 43.2533418,
               "lng" : -79.89254799999999
            }
         },
         "copyrights" : "Map data ©2022 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "32.2 km",
                  "value" : 32202
               },
               "duration" : {
                  "text" : "48 mins",
                  "value" : 2875
               },
               "end_address" : "236 Lakeshore Rd E, Oakville, ON L6J 1H7, Canada",
               "end_location" : {
                  "lat" : 43.4463994,
                  "lng" : -79.66751909999999
               },
               "start_address" : "246 Locke St S, Hamilton, ON L8P 4B9, Canada",
               "start_location" : {
                  "lat" : 43.2533418,
                  "lng" : -79.88666219999999
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 393
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 66
                     },
                     "end_location" : {
                        "lat" : 43.25441259999999,
                        "lng" : -79.89128719999999
                     },
                     "html_instructions" : "Head \u003cb\u003ewest\u003c/b\u003e on \u003cb\u003eCharlton Ave W\u003c/b\u003e toward \u003cb\u003eDundurn St S\u003c/b\u003e",
                     "polyline" : {
                        "points" : "k|~fGrzqfNg@hDaBfLw@pFSxA"
                     },
                     "start_location" : {
                        "lat" : 43.2533418,
                        "lng" : -79.88666219999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.6 km",
                        "value" : 1575
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 259
                     },
                     "end_location" : {
                        "lat" : 43.2678428,
                        "lng" : -79.88533219999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eDundurn St S\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ac_gGpwrfNkAa@eBm@QGaEuAoCu@c@QA?a@Oi@Qa@MEAWKi@QYICAAAi@Qi@SIA{@]k@QMQCCAAAA_A[qDiAqAc@w@UqAe@sAc@u@Sm@Q[C[Ii@Q_@MeA[}@YaA[aA[oAa@cA[eCw@g@QiA_@eBk@a@Mw@YYKYm@"
                     },
                     "start_location" : {
                        "lat" : 43.25441259999999,
                        "lng" : -79.89128719999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.5 km",
                        "value" : 1480
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 108
                     },
                     "end_location" : {
                        "lat" : 43.2802664,
                        "lng" : -79.89115489999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eYork Blvd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_wagGhrqfNSa@[PSJ_@Re@PkBj@[J]LC@IJUHuBh@A@eAXi@NeAX_APk@Hw@HSDI@I@WJ}Ar@kD`ByCvAWLUL_Ah@}JjG{Av@_Ab@YLiBn@EBu@RmA\\m@Pa@HiB`@QBQ?WHS@E?E@"
                     },
                     "start_location" : {
                        "lat" : 43.2678428,
                        "lng" : -79.88533219999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.5 km",
                        "value" : 1544
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 98
                     },
                     "end_location" : {
                        "lat" : 43.2934613,
                        "lng" : -79.8892427
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eYork Blvd\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "uddgGtvrfNIBkATaARa@FwB^aBZ]FYFK@eAReGfAA@u@JwATODy@H_@Be@?YA]CWCc@Ma@OKGgBaA_@U]Oq@[m@WiBy@w@a@mAq@w@_@q@QaAQ{@Eo@CwHYc@CUASASASESGCAWMSMCCOMQOMQMSKQISOo@"
                     },
                     "start_location" : {
                        "lat" : 43.2802664,
                        "lng" : -79.89115489999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "7.1 km",
                        "value" : 7077
                     },
                     "duration" : {
                        "text" : "10 mins",
                        "value" : 573
                     },
                     "end_location" : {
                        "lat" : 43.3279532,
                        "lng" : -79.8242053
                     },
                     "html_instructions" : "Continue onto \u003cb\u003ePlains Rd W\u003c/b\u003e",
                     "polyline" : {
                        "points" : "cwfgGvjrfNG]CSASAU?U?M?I@]B[LmAD[BS`@mDPoAp@uE^_CLs@bB{I@c@z@kE`@}BTgAJo@Ns@?CBKF[@EJk@@CJk@He@X{ATgBJgA@CH{ADgBBqAAyA?cBAc@IuAImAACMeAM{@Ic@EUWiAOk@K]GIEEKEOc@kA}Cy@sBWo@KUg@gA_@y@k@gAk@_A_@k@]e@mA{AIKaAcAoBiBOOMKOO[]SWUWq@w@cAoAgAqA{@aAY]cAkAqAuAW[WYOQw@}@KM{@cAGGg@q@k@w@m@_Aa@m@wAqBGIs@aAw@eA}@oAg@u@sAqBq@_Ac@m@k@{@a@m@QWQWgA_Be@s@cAuAwAoBiAeBYa@_ByBACs@cA}@qAq@aAeA}AaBaCqAkBwAwBk@y@[a@g@s@aB_CwAqB[c@_B{B]g@g@q@IKa@g@o@aAOSa@k@sEwG}@oAgBoC}@qAkAcBs@cAm@{@kFsHc@o@QYq@_Ae@s@s@cAS[SYq@aA]g@U]iAaBcA_B{@oAEGy@oAoAmB[e@OSmAkBaAyAYc@MQeCuDq@cAo@_ASYm@}@e@s@m@aAu@kAMc@?CMW}@mAq@eAOS_@g@?ACEMSOSm@{@wAoBkAaBy@gAKQOQCEq@_Am@w@aAkA[][[q@q@g@a@a@Yc@_@_@e@gC{Cm@aAMU_@u@q@wAWo@Wq@GWy@cD"
                     },
                     "start_location" : {
                        "lat" : 43.2934613,
                        "lng" : -79.8892427
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "3.1 km",
                        "value" : 3057
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 294
                     },
                     "end_location" : {
                        "lat" : 43.34693900000001,
                        "lng" : -79.7976946
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eFairview St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "unmgGhtefNk@_CSgAS}@YmAa@kBWiAUkAQw@ESWqAG[]uAAEOm@Ka@AEMa@M[EMIOUe@QYS[W]i@m@q@s@UUi@g@k@i@eAcA][c@]_@[qD_D][s@k@c@_@]]KI]]m@m@y@y@CCUWm@q@cAmAu@_AAAq@w@AAm@w@UWe@g@SSIGuAuAg@g@}AwAOQYYWYY]?Ao@y@y@kAo@aASYu@eAy@kAYg@u@kAU_@IM[m@Qa@c@o@OWACoA_D]y@e@kAUe@Sa@Ua@c@o@IM}BgDQYu@iAu@eAqAkBEEqAoBKMwCkEu@gAeBiC{@mAaBgCY_@Ya@K_@c@u@MMw@aA"
                     },
                     "start_location" : {
                        "lat" : 43.3279532,
                        "lng" : -79.8242053
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.4 km",
                        "value" : 1401
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 143
                     },
                     "end_location" : {
                        "lat" : 43.3382933,
                        "lng" : -79.785438
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eGuelph Line\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "keqgGpn`fNG]COAK?O@OF[vAoBDIv@gA|@qADGf@s@~@oAFKn@_A~AgCrAuBnCeEnB{CtAuBF[^i@RY`@g@vAwB`@m@fAcBBCpAoBn@_AvAuBx@qAd@s@b@o@XQZ[v@iAb@q@l@}@"
                     },
                     "start_location" : {
                        "lat" : 43.34693900000001,
                        "lng" : -79.7976946
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "6.2 km",
                        "value" : 6186
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 482
                     },
                     "end_location" : {
                        "lat" : 43.3815341,
                        "lng" : -79.73775569999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eNew St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ioogG~a~eNPYWU_CoCOQ]]SC[c@IIKM[]aBiBuB_CyA{AW[wC{C[]cCoCiBkBoByBoA}Ac@g@aAgAcAeAQSs@s@sA}AyAcBeBqB}BeCeEyEwAaBuA{AY[wA_B{DmEeAgAqBwBg@s@m@q@IKGOEK?A]]a@g@KQ{@aAq@q@UU_@a@UKMOe@k@i@m@a@c@GIuAsA}@cAUYSU}EqFcAgAgAqAqB}Bu@y@y@}@UWEEQSKMW[qB{Bo@u@gAoAc@g@CCyDgE_AcAiAoAsBaCe@i@e@i@]a@}BkCcAiAeAkAaG}Ge@i@{@}@sA_BkAqAECSg@gAqAQQu@{@k@s@k@m@y@aAEEY]UYCCkAwAeAmAYKwCeDsA{A_@c@UWy@_AgAqAOQ{AgBy@aAgAmAe@k@kAwAgBmB}BkCkBuBaAiAi@o@_EoEoB{BqFiGaBmBi@m@ACoAyAuBcC}@aAoC{CGII[U[aAmA"
                     },
                     "start_location" : {
                        "lat" : 43.3382933,
                        "lng" : -79.785438
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "8.7 km",
                        "value" : 8661
                     },
                     "duration" : {
                        "text" : "12 mins",
                        "value" : 730
                     },
                     "end_location" : {
                        "lat" : 43.442944,
                        "lng" : -79.67385929999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eRebecca St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "q}wgG~wteN_AgAACWUKGSWII[]UWc@e@u@y@cBiBwA_BeAgA?A_@c@SQ_AgA}BkC_@Qc@i@oB{BwAaBcCkCo@s@uA}AaEuEi@m@}@_Aw@{@aAaAOOmAwAg@i@AAACsA{A]a@YYw@y@yCqCCOACACKKSQmAqAu@w@QUOOGIUYaFcFa@i@gAuAeAuACE_BoBc@k@ACaBsBeAsAUYGIqByBCCmAsAuB}B[[iAkAq@u@u@s@yAaBgAqAw@}@y@aAQSoA}Au@y@qAwAkBuBsAwA{A_Bs@cAeAgAcBkBgAkAy@cAkHkIy@q@kAqAeEwEoAuAuCiDsA{AAAuA{AsB}BaCmCuA}AyBcCiBqBa@a@qA{A_@Uc@g@y@}@oDiEsAyAgEsEoBqBQSaAiAuCiDy@_A_AeAeAiAw@_AOM_AgAyAaB{@_AeAmAs@u@K[uA_BY]cBmBe@g@OAa@_@IUqCgDSUUUGGIIMKQMOKOKKGOIcA[AAWG[ESCQAM?U?i@A[@eAB]@}@D_CD]AW?]CUCa@G]GYG_@KQEOGQGEAWKKGOGe@S[S[UMK_@_@SUECMMAAKOeAuAe@m@gCcD_AmAs@}@k@u@ACgAuAa@k@k@o@MOMQq@y@m@w@k@u@c@i@Ya@AAKMiA{AY_@AAOSoA_Bg@m@_@o@[e@CEW_@S]O[ACe@y@[s@IOQc@GMa@eA]_Ae@{@OYKS]m@Wa@q@aAKMKMSWCEQQWYiBuBWYgAiAgAkA]e@_@]AC}AgBgDsDYEUU{BeCsByB"
                     },
                     "start_location" : {
                        "lat" : 43.3815341,
                        "lng" : -79.73775569999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 640
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 72
                     },
                     "end_location" : {
                        "lat" : 43.4474735,
                        "lng" : -79.66897929999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eRandall St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "k}chGrhheN[a@u@_AUWuAwAOSOOiCoCSMIK[[oBcCk@q@kAkAGIqAyAy@{@}AaBMO"
                     },
                     "start_location" : {
                        "lat" : 43.442944,
                        "lng" : -79.67385929999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 167
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 40
                     },
                     "end_location" : {
                        "lat" : 43.4465481,
                        "lng" : -79.66735659999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eDunn St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "uydhGbjgeNlAkCJS|AcD"
                     },
                     "start_location" : {
                        "lat" : 43.4474735,
                        "lng" : -79.66897929999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "21 m",
                        "value" : 21
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 10
                     },
                     "end_location" : {
                        "lat" : 43.4463994,
                        "lng" : -79.66751909999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e at the 2nd cross street onto \u003cb\u003eLakeshore Rd E\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the left\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}sdhG~_geN\\^"
                     },
                     "start_location" : {
                        "lat" : 43.4465481,
                        "lng" : -79.66735659999999
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "25.2 km",
                  "value" : 25161
               },
               "duration" : {
                  "text" : "38 mins",
                  "value" : 2299
               },
               "end_address" : "of Building, 3025 Lenworth Dr Unit 5&6 Rear, Mississauga, ON L4X 2G3, Canada",
               "end_location" : {
                  "lat" : 43.6210387,
                  "lng" : -79.5738975
               },
               "start_address" : "236 Lakeshore Rd E, Oakville, ON L6J 1H7, Canada",
               "start_location" : {
                  "lat" : 43.4463994,
                  "lng" : -79.66751909999999
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "7.3 km",
                        "value" : 7331
                     },
                     "duration" : {
                        "text" : "10 mins",
                        "value" : 580
                     },
                     "end_location" : {
                        "lat" : 43.4985802,
                        "lng" : -79.61329379999999
                     },
                     "html_instructions" : "Head \u003cb\u003enortheast\u003c/b\u003e on \u003cb\u003eLakeshore Rd E\u003c/b\u003e toward \u003cb\u003eDunn St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "_sdhG~`geN]_@sAyAmAsAsAyAoAwAmAqAmAuA{A{Aw@y@{@aAy@{@k@o@e@i@q@s@KKw@{@}@cAi@k@o@u@iAqAy@}@cBmBg@i@g@i@eAiAo@u@cAiAcCmCq@w@wDaEy@_AwA{As@y@QQ_@c@k@q@_FqFm@o@qAwAMMSUcAgAyA_Bo@s@gBiBo@u@iAuA}@eAw@}@eAkA{BcCs@{@IKUUsAuAa@e@g@k@qByBy@}@q@u@mBuBw@}@kD}D{@_AsAwAy@{@c@g@GGKO_AeAkAsAi@m@]a@mAsAsA{AoB}BiDwDmCyCKMgAmAcAiAUWEEsA{AQUg@i@kBsB{BgCy@}@u@y@wL}MKKgCqC{@aA}@aAW[IGmAsAGGgBoBIIkBuBk@m@cAgA]_@{@_Aw@y@GGoAsAs@o@o@u@kAqAqBuBoAsA_FkFsB_CiBoB_@a@mAsAaAgAIIeBqB[]qAuAcBoBkCuCc@e@{BaCuC_DuEgFkCwCgFwFOQ]][_@[]YYACiDuDi@m@gAkAGGKGOKQIQGOGOCQCSAQAK@K?UDUDKD[NGBCBGFGDIH[^"
                     },
                     "start_location" : {
                        "lat" : 43.4463994,
                        "lng" : -79.66751909999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.9 km",
                        "value" : 1867
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 152
                     },
                     "end_location" : {
                        "lat" : 43.5106717,
                        "lng" : -79.6293383
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eSouthdown Rd\u003c/b\u003e",
                     "polyline" : {
                        "points" : "cynhG`n|dN{@pAW`@{BdDaB`CyBbD_DxEmBtCmErG]d@[d@cAzA_@j@GH_@j@}@pA{BfD{AvB}A~Bq@`AKNaB~BQXW^aB`Cw@hAoBrC_ArA_AtA_AtAKLILmAbBw@l@gA`Bw@lA"
                     },
                     "start_location" : {
                        "lat" : 43.4985802,
                        "lng" : -79.61329379999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "10.4 km",
                        "value" : 10375
                     },
                     "duration" : {
                        "text" : "16 mins",
                        "value" : 953
                     },
                     "end_location" : {
                        "lat" : 43.5843411,
                        "lng" : -79.5508926
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eLakeshore Rd W\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "udqhGjr_eNa@TQHKBI?M?QGSKWO]IY[CCSGq@s@c@g@{@eAo@s@c@e@gBsByAaBMMg@i@eAkAk@o@q@u@s@w@q@u@m@q@}AeBQSe@g@KKa@e@q@y@{@aA[]m@q@qC_DQQ_AeAaAiAo@q@a@e@UWm@q@e@k@CAaAiAsA_Bi@o@GIcAmAmAeAaAcAqB{BUWg@k@KMY]KK{AgBKKqA}AyAcBYY}AeBk@o@kBuB}AeB_@c@wBgCgBmBsAwAy@_AOSg@i@s@w@qB_CoB{BiCwC]]q@s@}@cAw@eAs@u@w@y@gAmAKK{AcBqC_DYYw@}@e@i@[]WWu@w@mAqAEGoCuCy@}@[_@[]y@{@s@w@W[_AeAy@}@[]w@}@q@u@[]w@{@_CmCi@o@cAiAQSy@{@[_@mAsAk@o@k@m@MOs@u@cAgAgAiAo@q@oB}Bk@q@k@o@k@m@m@q@[_@W[GGeAmAkCwCeAmAeAkAm@u@[_@GI{AgBa@a@g@k@{@aAw@cAu@{@]_@w@{@IKQSw@{@}@aAa@c@q@u@aAcAY]]a@o@s@KMe@k@a@e@o@w@KMy@aAW[g@k@{@_AQQy@_Ao@s@GIqB}Bw@y@EEk@k@GIMKm@m@k@m@w@{@cAkACCMOmAwAcAiA_A_AsAyAeAgAcAkAy@}@mAqAiAoA_AcA}@_AmAsAyA}A[]OQk@m@}AcBy@}@yB_CaBiBeAgAe@i@KKq@s@gAoA}@cAgAgAgAmAw@y@iBoBaBgBq@q@ACMM_@c@a@c@SUMMUWg@i@g@k@[[Y[mDyDUW{@}@a@c@k@m@w@u@MQg@k@q@u@MOk@o@]_@c@e@o@q@}@_Ak@q@_BeBg@m@o@q@k@m@OQQQOQcBiB_AaASSq@u@SUk@m@w@{@e@g@qAsA[]UUsAyAk@o@y@w@OQq@w@cAiA}@_A{DeE}@aA}A}A}@_Aa@e@MMOSuC{Ce@g@{@aAgBmB]]SUmCuCq@s@c@g@oDwDgAmA"
                     },
                     "start_location" : {
                        "lat" : 43.5106717,
                        "lng" : -79.6293383
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.4 km",
                        "value" : 2381
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 221
                     },
                     "end_location" : {
                        "lat" : 43.59957,
                        "lng" : -79.57015489999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eDixie Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003ePeel Regional Rd 4 N\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "cq_iG`hpdNsCrEODi@x@_AtAc@r@kAjBe@t@KNq@fA}AdC_AxAQXWb@s@hACBU^q@dAy@rAQVAB[d@w@lA{@tAu@lAkAhBI^q@dAyC|EY`@wCtEgBzCaAvAkAhB[f@Yb@KPKPILKRU`@Wd@G@A@C@GDIJGJs@pAUh@g@|@y@`Bo@xAINEJCFAHAJKRS`@Wf@GJc@`AWd@k@lAYl@?@Ub@A@IRCFABCDKR?@Q^KT[l@KPMNMNMLOJOHMHMDMDI@E@OBQ@S?S@YAsA@g@Bq@@E?M@MAIAKCGEGGGGIO"
                     },
                     "start_location" : {
                        "lat" : 43.5843411,
                        "lng" : -79.5508926
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.5 km",
                        "value" : 1534
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 212
                     },
                     "end_location" : {
                        "lat" : 43.6091864,
                        "lng" : -79.58349559999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eDixie Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003ePeel Regional Rd 4 N\u003c/b\u003e (signs for \u003cb\u003eDixie Road N\u003c/b\u003e)",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ipbiGl`tdNQUw@nAcAdByA|BeAbBaBjCy@nAg@v@k@|@KNuAtBc@p@GLEDQTw@nAuA|BsAxBaBjC}BnDS^m@~@cBnC]h@SZq@fA{BrDm@`Aq@fAoA~AITCLCTk@`AKROVI@G?CBUNaAxA"
                     },
                     "start_location" : {
                        "lat" : 43.59957,
                        "lng" : -79.57015489999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.4 km",
                        "value" : 1374
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 134
                     },
                     "end_location" : {
                        "lat" : 43.6190261,
                        "lng" : -79.57338439999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eDundas St E\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "mldiGzsvdNUBC?C?E?E?_@IOSg@o@y@cAAACEUYQUKKCAC?E?C@MOIIy@_AEGQOKMcAgAs@y@UWIKy@_AeBoBgBoBIKi@m@a@a@i@k@q@q@eAmAgAkAw@u@k@m@o@u@OQgAkAq@u@]a@g@g@MOIIMMGEW[KKk@m@q@s@OQGIs@u@u@w@OQMMm@m@_@a@WWw@y@"
                     },
                     "start_location" : {
                        "lat" : 43.6091864,
                        "lng" : -79.58349559999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 172
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 28
                     },
                     "end_location" : {
                        "lat" : 43.6201343,
                        "lng" : -79.5748658
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eWharton Way\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}ifiGrttdN{@lAINg@n@}@tAo@dA"
                     },
                     "start_location" : {
                        "lat" : 43.6190261,
                        "lng" : -79.57338439999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 127
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 19
                     },
                     "end_location" : {
                        "lat" : 43.6210387,
                        "lng" : -79.5738975
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eLenworth Dr\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ypfiG|}tdN}AcBkAsAKI"
                     },
                     "start_location" : {
                        "lat" : 43.6201343,
                        "lng" : -79.5748658
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "7.2 km",
                  "value" : 7151
               },
               "duration" : {
                  "text" : "13 mins",
                  "value" : 804
               },
               "end_address" : "927 The Queensway, Etobicoke, ON M8Z 5Z7, Canada",
               "end_location" : {
                  "lat" : 43.623808,
                  "lng" : -79.5114822
               },
               "start_address" : "of Building, 3025 Lenworth Dr Unit 5&6 Rear, Mississauga, ON L4X 2G3, Canada",
               "start_location" : {
                  "lat" : 43.6210387,
                  "lng" : -79.5738975
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 127
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 20
                     },
                     "end_location" : {
                        "lat" : 43.6201343,
                        "lng" : -79.5748658
                     },
                     "html_instructions" : "Head \u003cb\u003esouthwest\u003c/b\u003e on \u003cb\u003eLenworth Dr\u003c/b\u003e toward \u003cb\u003eWharton Way\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ovfiGzwtdNJHjArA|AbB"
                     },
                     "start_location" : {
                        "lat" : 43.6210387,
                        "lng" : -79.5738975
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 172
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 39
                     },
                     "end_location" : {
                        "lat" : 43.6190261,
                        "lng" : -79.57338439999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eWharton Way\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ypfiG|}tdNn@eA|@uAf@o@HOz@mA"
                     },
                     "start_location" : {
                        "lat" : 43.6201343,
                        "lng" : -79.5748658
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.9 km",
                        "value" : 1939
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 197
                     },
                     "end_location" : {
                        "lat" : 43.6289647,
                        "lng" : -79.5549123
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eDundas St E\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}ifiGrttdNy@y@W[Y]c@c@CEW]i@k@e@e@c@g@QQII{A}ASSi@i@e@c@WUw@}@gAqAm@o@s@w@oAuA_@a@gAqAiAeAUS]_@s@s@YYMMi@k@i@k@A?OQ[[[]CCUY[a@OQOYSYEGc@{@O]GMKUACK[CEMe@Ss@Ka@?_@AQCUAIc@mCMu@M}@Ky@]yBScBS_BK}@?I?E_@_DEYGe@AO}@aHGk@]_CQ}@G_@CMCOESAEAKEOEYQaA_@uB"
                     },
                     "start_location" : {
                        "lat" : 43.6190261,
                        "lng" : -79.57338439999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 907
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 98
                     },
                     "end_location" : {
                        "lat" : 43.63214929999999,
                        "lng" : -79.544673
                     },
                     "html_instructions" : "Take the ramp to \u003cb\u003eDundas St W\u003c/b\u003e",
                     "polyline" : {
                        "points" : "_hhiGdaqdNGSCUSeAAGOs@Kk@Kc@Ga@Ic@EWG]Ig@SaAUoAKo@Mq@Ke@CQCKG[?OEOEWGc@G[Ga@G[AKAI?AAKAEE[CUCUM{@AQG_@COE]AICGACCCCAGAQ}AGi@CSG]Ii@Kq@Os@Kc@Om@Sq@O]KUM]?AEKe@gAEMCGMYEMSa@Qc@KUKY"
                     },
                     "start_location" : {
                        "lat" : 43.6289647,
                        "lng" : -79.5549123
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.1 km",
                        "value" : 1133
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 106
                     },
                     "end_location" : {
                        "lat" : 43.6224734,
                        "lng" : -79.5406208
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eShorncliffe Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}{hiGdaodNTM@?^S`@SJGJA@?@?BA@ABCHEb@e@HILOLI?AJGNKJGJELEFCJENAFAb@Eb@GTCL?ZEj@GHAVCDANAD?BAB?@A@A@C@CJAD?XERAf@GHAHAHC@?HALEPEBAj@QDARGJEBANERIh@Ql@Sr@U`@KZKDAVKHCTGPGPG^KPGzAg@NEf@QLETILETIPGJCZKj@Sb@Ob@Of@QLEb@Oh@QzAg@NEbA]"
                     },
                     "start_location" : {
                        "lat" : 43.63214929999999,
                        "lng" : -79.544673
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 1022
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 97
                     },
                     "end_location" : {
                        "lat" : 43.6252387,
                        "lng" : -79.52850979999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eN Queen St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "m_giGzgndNSsACUCQMy@Kw@Ko@Ik@Gg@EYM}@ACKy@G_@a@wCGa@Io@Ga@M{@Im@Ga@_@iCCMQoAm@gEOcAE]Ko@UaBYwBYwBEUK{@AE]{BCSKq@Gk@CSKk@Iq@Ki@O_A"
                     },
                     "start_location" : {
                        "lat" : 43.6224734,
                        "lng" : -79.5406208
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 491
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 59
                     },
                     "end_location" : {
                        "lat" : 43.6210063,
                        "lng" : -79.526877
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eKipling Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wpgiGd|kdNr@MBAh@MF?FCFA@?HCZKf@OFABAr@Wp@SNEnAa@VIr@Ul@Sr@UXI^Md@QZIJEHDB@D?FA\\M`A]"
                     },
                     "start_location" : {
                        "lat" : 43.6252387,
                        "lng" : -79.52850979999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1301
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 176
                     },
                     "end_location" : {
                        "lat" : 43.6243196,
                        "lng" : -79.51169539999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eThe Queensway\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ivfiG~qkdNZKEc@c@yCESAICECGIMCOQmA]eCIi@QmAQqAM_AQqAOgAOeAo@oEYaCMcAIk@HU?A?ACUU{AWmBYsBWkBYyBSsAKaAMy@Is@YeBC[G_@k@_ESSKu@[kBQwAM}@OaA"
                     },
                     "start_location" : {
                        "lat" : 43.6210063,
                        "lng" : -79.526877
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "59 m",
                        "value" : 59
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 12
                     },
                     "end_location" : {
                        "lat" : 43.623808,
                        "lng" : -79.5114822
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eCanmotor Ave\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the left\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_kgiGbshdNd@Ob@OPGHC"
                     },
                     "start_location" : {
                        "lat" : 43.6243196,
                        "lng" : -79.51169539999999
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "6.1 km",
                  "value" : 6070
               },
               "duration" : {
                  "text" : "13 mins",
                  "value" : 751
               },
               "end_address" : "1537A Queen St W, Toronto, ON M6R 1A7, Canada",
               "end_location" : {
                  "lat" : 43.6393792,
                  "lng" : -79.4428415
               },
               "start_address" : "927 The Queensway, Etobicoke, ON M8Z 5Z7, Canada",
               "start_location" : {
                  "lat" : 43.623808,
                  "lng" : -79.5114822
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "59 m",
                        "value" : 59
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 24
                     },
                     "end_location" : {
                        "lat" : 43.6243196,
                        "lng" : -79.51169539999999
                     },
                     "html_instructions" : "Head \u003cb\u003enorth\u003c/b\u003e on \u003cb\u003eCanmotor Ave\u003c/b\u003e toward \u003cb\u003eThe Queensway\u003c/b\u003e",
                     "polyline" : {
                        "points" : "yggiGvqhdNIBQFc@Ne@N"
                     },
                     "start_location" : {
                        "lat" : 43.623808,
                        "lng" : -79.5114822
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "5.7 km",
                        "value" : 5663
                     },
                     "duration" : {
                        "text" : "11 mins",
                        "value" : 656
                     },
                     "end_location" : {
                        "lat" : 43.63850860000001,
                        "lng" : -79.4469783
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eThe Queensway\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_kgiGbshdNS{AKm@UeBUeBWkBMy@OaAc@aDC_@GYQgAE_@M_AS}ACQCMIu@_@gCKw@Ko@MaAUgBIo@Ik@e@mDGg@a@uCCOE[EUa@wCMu@_@uCUeBIm@Ik@Is@i@_EKk@e@oDOeA_@yCWuBUcBE_@M}@Im@e@gDIo@Ko@CUKu@Gc@U}AIi@U_BC_@EUEWIs@WqBG_@Ge@E]Gm@Ic@YsBCYMy@AOGa@Gg@CYIg@Gc@CQUaBQsAAMAGIm@]yBKy@Ic@I{@SsAK_AGa@@S?ECMCWIi@QsAMs@OaAACWmBIe@Gk@Eg@AIEa@AMC[Gi@Ei@I{@Gq@AKEa@AMC[CUCSCUCSCSESESESISGQIOIQKOKOKMKKMMYSOMOIAAKIKIGEEEMIMKMIKKEEi@i@[[]_@QSII[][[OOMMKMIKSQMOIKIIGGY[OOIICEKKIISSIIm@o@k@o@SU_@e@IKMOKOIMKQIOKOKQIQEKEIEIKSOa@IUSm@K_@Ke@GWESEQGWCSEUCUEUEg@Ek@Gs@C_@Gu@IkAWwCOeBIq@c@mDMm@E[O_AOw@Gc@G]ScAKg@Mm@CIWqAMm@Kc@Ou@Mm@GWEUWqAMy@EUEY?AGi@M}@OsAK_AKcAKsAAMGo@Eo@IaBEw@AOAk@GiC?aA?Y?WAq@?K?wA?o@?_@?cA?q@?uC?o@?Q?g@?gA?WAq@?g@@U?G?G@Q?G@MB[@M?ADO@MBOB[@GBKJe@BMBKBM@EBEBCDOBO@EBMBUHw@D[LgABWDc@Ho@B]VuBNuAToBDYJy@@Q@G?q@A_@"
                     },
                     "start_location" : {
                        "lat" : 43.6243196,
                        "lng" : -79.51169539999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "76 m",
                        "value" : 76
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 17
                     },
                     "end_location" : {
                        "lat" : 43.63870379999999,
                        "lng" : -79.44608459999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eThe Queensway\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "ucjiGr~{cNCE?C?CCMAQAMAOCYCQEUIe@"
                     },
                     "start_location" : {
                        "lat" : 43.63850860000001,
                        "lng" : -79.4469783
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 272
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 54
                     },
                     "end_location" : {
                        "lat" : 43.6393792,
                        "lng" : -79.4428415
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eQueen St W\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "polyline" : {
                        "points" : "{djiG~x{cNQc@[oCIo@Go@E[AQMeAIs@CQc@yD"
                     },
                     "start_location" : {
                        "lat" : 43.63870379999999,
                        "lng" : -79.44608459999999
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "k|~fGrzqfNuE|[eKmDaIeCcFeB_Ai@eIkCcLeDaQqFyFkBqAe@m@oAuBbAiDfAwC`AuFtAaCZ_C`A}IfEoPzJiEdBsElAoEv@mM~BeQrCuBIyDgBeMgG_Fm@eKa@_C_Ay@gAe@uBN_F|@mHbEeVtCiP|AgJ\\oG?sHc@mFu@_EkEuKkBgEuCyEsI_JaKuLyGuHoJ{MoY{a@{\\if@}`@sk@_Tg[sLoQwD_GyAmCqDmF}I{LyGsGcFyGaCoFiFeU}BoKaBcEyHgIgL{J}GkHiFgGaIaIqNsTiDkIwAaCqLaQoJkNaDiFqBcDC{@hI{LjFiI|IsNlJiNfF{HpCgDpAoBPYWUoCaDq@a@mAyAiIaJgU}V{OgQyYa\\mDuEyFeGoNuOk[a^iPaRiLqMyD}EaIgJkDcEeHqHkL_NyXm[sWeZiBoCeBiBeJaK{JoKsa@qd@wUuV{KoNyLcNea@gd@m\\y^gWqY}FeGaJiKaV}WcLwMyFsGq@a@{C}D{@}@_Aq@{DcAkKPcFm@sCgAoC_C_VyZaEmFsFcIgDyHaEwGsIoJ}CoDsIuI{M_O{J{KwC}CMOlAkChBwD\\^]_@aDmDcDqDoH}H{JwKwM}Ngc@cf@_~@icAmkAyqAud@{f@cm@sp@sIyIaCYoBv@qRbYg`@pk@mNlSwE`GyAbB]L}@SsAy@eDiDuGoHmJiKmImJ_XuZqJaKcP{Qic@}f@m\\k^iq@qu@uk@mp@ar@yu@yu@ey@aj@ul@__@u`@_N}NwFeGcDxEmCbE_JrNeFfIeEvGaHlLiNrT}A`CuFrKqFnL}@pBcA~A{@l@uBVsFBc@Y[e@{BtD{H|LuDzFgKnPcO`VyD~F_AxBe@\\wAhBYBo@IsBiCiAaAkRaT{R}ScGsGkBoBoAqAeA|AeBdCo@dA}AcBwA}AvA|A|AbBn@eAdBeCdA}AoCwCkBuBwGyGiUoV}CwDoB_Eq@aCGqA}CwT_EoZqDaSkEmX_AkFuB{H}AuD]y@KYTM`@Sl@[RCr@q@xAgAjH}@vCg@pJwC`KeDtFkBxE}Ai@uDkAqIcBwLqGmd@a@}C[iBv@O`ASnA_@|GwBhFcBZD~Ak@ZKEc@i@mDEOc@sBkCoRaBaMDo@gDsVo@uE_AsEg@aD_@uCOaAd@Ot@Wu@Ve@NS{Aa@sCm@qEeA}Hm@aEkBeNmGie@yMybAcD}U}CiVmAwMu@yCqB{BsFaFmFyF_EoE{AcCwAyDu@{DgAwMyBkPiEsTkAcLi@aOC_X`@_GvA{IbBaOEgCo@{DqAiLc@yD"
         },
         "summary" : "Rebecca St",
         "warnings" : [],
         "waypoint_order" : [ 0, 1, 2 ]
      }
   ],
   "status" : "OK"
}
```
____
## Rubric

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown with a unique origin and destination earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%
4. Including more than 2 "stops", including links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%. 
