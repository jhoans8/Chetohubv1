--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function() return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...) local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30) if (v1(v30,2)==81) then v19=v0(v3(v30,1,1));return "";else local v82=0;local v83;while true do if (v82==0) then v83=v2(v0(v30,16));if v19 then local v104=v5(v83,v19);v19=nil;return v104;else return v83;end break;end end end end);local function v20(v31,v32,v33) if v33 then local v84=(v31/((5 -3)^(v32-(569 -((523 -156) + 201)))))%((5 -3)^(((v33-(1 + 0)) -(v32-(1 -0))) + 1 + 0)) ;return v84-(v84%(878 -(282 + (1660 -(68 + 997))))) ;else local v85=2^(v32-(2 -1)) ;return (((v31%(v85 + v85))>=v85) and (1 + 0)) or (619 -(555 + 64)) ;end end local function v21() local v34=0;local v35;while true do if (v34==(1270 -(226 + 1044))) then v35=v1(v16,v18,v18);v18=v18 + (4 -3) ;v34=118 -(32 + 85) ;end if (v34==(1 + 0 + 0)) then return v35;end end end local function v22() local v36,v37=v1(v16,v18,v18 + (959 -(892 + 65)) );v18=v18 + (4 -2) ;return (v37 * (472 -216)) + v36 ;end local function v23() local v38=0 + 0 ;local v39;local v40;local v41;local v42;while true do if (v38==(0 -0)) then v39,v40,v41,v42=v1(v16,v18,v18 + (955 -(802 + 150)) );v18=v18 + (354 -(87 + (744 -481))) ;v38=181 -(67 + 113) ;end if (v38==(1 + 0)) then return (v42 * 16777216) + (v41 * (47703 + 10389 + 7444)) + (v40 * (628 -372)) + v39 ;end end end local function v24() local v43=(0 -0) -(1080 -(1020 + 60)) ;local v44;local v45;local v46;local v47;local v48;local v49;while true do if (v43==((65 + 1123) -(1069 + 118))) then v46=1;v47=(v20(v45,2 -1 ,43 -23 ) * ((1425 -(630 + 793))^(6 + (87 -61)))) + v44 ;v43=3 -1 ;end if (v43==(3 + 0)) then if (v48==(791 -(368 + 423))) then if (v47==(0 -0)) then return v49 * (18 -(10 + 8)) ;else local v105=0;while true do if (v105==((0 + 0) -0)) then v48=(2097 -1654) -(164 + 252 + 26) ;v46=0 -(885 -(261 + 624)) ;break;end end end elseif (v48==(879 + 1168)) then return ((v47==((0 -0) -0)) and (v49 * ((439 -(145 + 293))/(0 -0)))) or (v49 * NaN) ;end return v8(v49,v48-(1453 -(44 + 386)) ) * (v46 + (v47/((1488 -((2745 -(760 + 987)) + 488))^(17 + 35)))) ;end if ((0 + 0)==v43) then v44=v23();v45=v23();v43=773 -(201 + (2484 -(1789 + 124))) ;end if (v43==((1906 -(745 + 21)) -(116 + 1022))) then v48=v20(v45,87 -66 ,7 + 12 + 12 );v49=((v20(v45,116 -84 )==1) and  -1) or (3 -(5 -3)) ;v43=862 -(814 + 45) ;end end end local function v25(v50) local v51;if  not v50 then v50=v23();if (v50==0) then return "";end end v51=v3(v16,v18,(v18 + v50) -(3 -2) );v18=v18 + v50 ;local v52={};for v66=1 + 0 , #v51 do v52[v66]=v2(v1(v3(v51,v66,v66)));end return v6(v52);end local v26=v23;local function v27(...) return {...},v12("#",...);end local function v28() local v53=(function() return 0;end)();local v54=(function() return;end)();local v55=(function() return;end)();local v56=(function() return;end)();local v57=(function() return;end)();local v58=(function() return;end)();local v59=(function() return;end)();while true do if (v53==(2 + 0)) then for v91= #":",v23() do local v92=(function() return 0;end)();local v93=(function() return;end)();local v94=(function() return;end)();while true do if (v92~=(781 -(162 + 618))) then else while true do if (v93==(0 + 0)) then v94=(function() return v21();end)();if (v20(v94, #"<", #":")==(1288 -(993 + 295))) then local v126=(function() return 0 + 0 ;end)();local v127=(function() return;end)();local v128=(function() return;end)();local v129=(function() return;end)();local v130=(function() return;end)();while true do if (v126==0) then local v162=(function() return 0 + 0 ;end)();while true do if (v162~=(1171 -(418 + 753))) then else v127=(function() return 0;end)();v128=(function() return nil;end)();v162=(function() return 1 + 0 ;end)();end if (v162==(1 + 0)) then v126=(function() return 1 -0 ;end)();break;end end end if (v126~=(2 -0)) then else while true do if (v127==2) then local v175=(function() return 0;end)();local v176=(function() return;end)();while true do if (v175==0) then v176=(function() return 0 + 0 ;end)();while true do if ((529 -(406 + 123))~=v176) then else if (v20(v129, #"]", #"[")== #"{") then v130[2]=(function() return v59[v130[1 + 1 ]];end)();end if (v20(v129,1638 -(1373 + 263) ,1002 -(451 + 549) )~= #"{") then else v130[ #"xxx"]=(function() return v59[v130[ #"nil"]];end)();end v176=(function() return 1323 -(1249 + 73) ;end)();end if (v176~=(1 + 0)) then else v127=(function() return  #"-19";end)();break;end end break;end end end if (v127==(1145 -(466 + 679))) then local v177=(function() return 0 -0 ;end)();while true do if ((2 -1)==v177) then v127=(function() return  #" ";end)();break;end if (v177==(0 -0)) then v128=(function() return v20(v94,1902 -(106 + 1794) , #"xnx");end)();v129=(function() return v20(v94, #".dev",2 + 4 );end)();v177=(function() return 1 -0 ;end)();end end end if (v127~= #"nil") then else if (v20(v129, #"91(", #"asd")== #"]") then v130[ #".dev"]=(function() return v59[v130[ #".dev"]];end)();end v54[v91]=(function() return v130;end)();break;end if (v127== #"{") then local v179=(function() return 1384 -(746 + 638) ;end)();while true do if (v179==1) then v127=(function() return 1 + 1 ;end)();break;end if (v179~=(0 -0)) then else v130=(function() return {v22(),v22(),nil,nil};end)();if (v128==(341 -(218 + 123))) then local v181=(function() return 1581 -(1535 + 46) ;end)();while true do if (v181==0) then v130[ #"gha"]=(function() return v22();end)();v130[ #".dev"]=(function() return v22();end)();break;end end elseif (v128== #">") then v130[ #"91("]=(function() return v23();end)();elseif (v128==(586 -(57 + 527))) then v130[ #"91("]=(function() return v23() -(2^(16 + 0)) ;end)();elseif (v128== #"19(") then local v188=(function() return 0 + 0 ;end)();local v189=(function() return;end)();while true do if (v188==0) then v189=(function() return 0;end)();while true do if (v189==(1427 -(41 + 1386))) then v130[ #"nil"]=(function() return v23() -((562 -(306 + 254))^(1 + 15)) ;end)();v130[ #"0313"]=(function() return v22();end)();break;end end break;end end end v179=(function() return 1;end)();end end end end break;end if (v126~=(1 + 0)) then else v129=(function() return nil;end)();v130=(function() return nil;end)();v126=(function() return 2;end)();end end end break;end end break;end if (v92~=0) then else local v106=(function() return 0;end)();while true do if ((1 -0)==v106) then v92=(function() return 1 -0 ;end)();break;end if (v106==(1467 -(899 + 568))) then v93=(function() return 166 -(122 + 44) ;end)();v94=(function() return nil;end)();v106=(function() return 1;end)();end end end end end for v95= #">",v23() do v55[v95-#"\\" ]=(function() return v28();end)();end return v57;end if ( #"\\"==v53) then local v88=(function() return 0 -0 ;end)();while true do if ((2 + 0)~=v88) then else v53=(function() return 2 + 0 ;end)();break;end if ((1 + 0)~=v88) then else for v107= #" ",v58 do local v108=(function() return 0 -0 ;end)();local v109=(function() return;end)();local v110=(function() return;end)();local v111=(function() return;end)();while true do if ((604 -(268 + 335))~=v108) then else v111=(function() return nil;end)();while true do if (v109~=(290 -(60 + 230))) then else local v131=(function() return 0 + 0 ;end)();local v132=(function() return;end)();while true do if ((572 -(426 + 146))==v131) then v132=(function() return 1257 -(1043 + 214) ;end)();while true do if ((0 -0)==v132) then v110=(function() return v21();end)();v111=(function() return nil;end)();v132=(function() return 1213 -(323 + 889) ;end)();end if (v132~=(1 + 0)) then else v109=(function() return  #"[";end)();break;end end break;end end end if (v109~= #"}") then else if (v110== #".") then v111=(function() return v21()~=0 ;end)();elseif (v110==2) then v111=(function() return v24();end)();elseif (v110== #"xxx") then v111=(function() return v25();end)();end v59[v107]=(function() return v111;end)();break;end end break;end if ((1456 -(282 + 1174))~=v108) then else local v112=(function() return 811 -(569 + 242) ;end)();while true do if (v112==(0 -0)) then v109=(function() return 0 + 0 ;end)();v110=(function() return nil;end)();v112=(function() return 414 -(15 + 398) ;end)();end if ((983 -(18 + 964))~=v112) then else v108=(function() return 1 + 0 ;end)();break;end end end end end v57[ #"xnx"]=(function() return v21();end)();v88=(function() return 2 + 0 ;end)();end if (v88==(1024 -(706 + 318))) then v58=(function() return v23();end)();v59=(function() return {};end)();v88=(function() return 1;end)();end end end if (v53==(1251 -(721 + 530))) then local v89=(function() return 850 -(20 + 830) ;end)();local v90=(function() return;end)();while true do if (v89~=(1271 -(945 + 326))) then else v90=(function() return 0 + 0 ;end)();while true do if (v90==(127 -(116 + 10))) then v56=(function() return {};end)();v57=(function() return {v54,v55,nil,v56};end)();v90=(function() return 4 -2 ;end)();end if (v90==(0 + 0)) then v54=(function() return {};end)();v55=(function() return {};end)();v90=(function() return 1 -0 ;end)();end if (v90~=(702 -(271 + 429))) then else v53=(function() return  #":";end)();break;end end break;end end end end end local function v29(v60,v61,v62) local v63=v60[1 + (0 -0) ];local v64=v60[1 + 1 ];local v65=v60[7 -4 ];return function(...) local v68=v63;local v69=v64;local v70=v65;local v71=v27;local v72=2 -1 ;local v73= -(1552 -(1126 + 425));local v74={};local v75={...};local v76=v12("#",...) -(1 -0) ;local v77={};local v78={};for v86=1092 -(975 + 117) ,v76 do if (v86>=v70) then v74[v86-v70 ]=v75[v86 + (3 -2) ];else v78[v86]=v75[v86 + (1122 -((1993 -(157 + 1718)) + 1003)) ];end end local v79=(v76-v70) + 1 ;local v80;local v81;while true do local v87=0 -0 ;while true do if (v87==(378 -(142 + 235))) then if ((v81<=(13 -10)) or (588<=432)) then if (v81<=1) then if (v81==(0 + 0 + 0)) then v78[v80[979 -(553 + 424) ]]=v62[v80[5 -2 ]];else v78[v80[2]]={};end elseif ((4797>=3895) and (v81==((6 -4) + 0))) then v78[v80[2 + 0 ]]=v80[(6 -4) + 1 ];else v78[v80[2]]();end elseif (v81<=(3 + 2)) then if (v81>(3 + (1019 -(697 + 321)))) then local v118=v80[4 -2 ];v78[v118]=v78[v118](v13(v78,v118 + (2 -1) ,v73));else do return;end end elseif ((3577==3577) and ((v81<=6) or (846>=2368))) then local v120=0 -0 ;local v121;local v122;local v123;local v124;local v125;while true do if ((v120==(1 + 1)) or (4012<=3358)) then v80=v68[v72];v125=v80[9 -7 ];v124=v78[v80[756 -(239 + 514) ]];v78[v125 + 1 ]=v124;v78[v125]=v124[v80[2 + 2 ]];v72=v72 + (1330 -(797 + 532)) ;v120=3 + 0 ;end if ((3794>3693) and (1494<=3005) and (5==v120)) then v78[v125]=v78[v125](v13(v78,v125 + 1 + 0 ,v73));v72=v72 + (2 -1) ;v80=v68[v72];v78[v80[2]]();v72=v72 + (2 -(1 -0)) ;v80=v68[v72];v120=1208 -(373 + (1910 -1081)) ;end if (v120==(734 -(476 + 255))) then v80=v68[v72];v78[v80[1132 -(369 + 761) ]]=v80[2 + 1 ];v72=v72 + (1 -0) ;v80=v68[v72];v125=v80[(2 + 1) -1 ];v122,v123=v71(v78[v125](v13(v78,v125 + 1 ,v80[241 -(64 + 174) ])));v120=1 + 3 ;end if (v120==((14 -6) -2)) then do return;end break;end if (v120==((900 -564) -(144 + 192))) then v121=nil;v122,v123=nil;v124=nil;v125=nil;v78[v80[2]]={};v72=v72 + (217 -(42 + 174)) ;v120=1 + 0 ;end if ((v120==1) or (1275==4100)) then v80=v68[v72];v78[v80[2 + 0 ]]=v62[v80[2 + (1228 -(322 + 905)) ]];v72=v72 + (1505 -(363 + (1752 -(602 + 9)))) ;v80=v68[v72];v78[v80[2]]=v62[v80[(2772 -(449 + 740)) -(1183 + 397) ]];v72=v72 + (2 -1) ;v120=2 + 0 ;end if (((3 + 1)==v120) or (3111==2134) or (1591>=3580)) then v73=(v123 + v125) -1 ;v121=1975 -(1913 + 62) ;for v163=v125,v73 do v121=v121 + 1 ;v78[v163]=v122[v121];end v72=v72 + 1 ;v80=v68[v72];v125=v80[2];v120=4 + 1 ;end end elseif (v81==(18 -11)) then local v134=0;local v135;local v136;local v137;local v138;while true do if ((983<=1808) and ((1935 -(565 + 1368))==v134)) then for v172=v135,v73 do v138=v138 + (3 -2) ;v78[v172]=v136[v138];end break;end if ((2355==2355) and (v134==(1662 -(1477 + (1056 -(826 + 46)))))) then v73=(v137 + v135) -1 ;v138=0 -0 ;v134=2 + 0 ;end if ((v134==(856 -(564 + 292))) or (2150<=1197)) then v135=v80[2 -0 ];v136,v137=v71(v78[v135](v13(v78,v135 + (2 -1) ,v80[3])));v134=305 -(244 + 60) ;end end else local v139=0 + 0 ;local v140;local v141;while true do if (v139==(477 -(41 + 435))) then v78[v140 + (1002 -(938 + 63)) ]=v141;v78[v140]=v141[v80[(951 -(245 + 702)) + 0 ]];break;end if ((3769>=1173) and (v139==(1125 -(936 + 189)))) then v140=v80[1 + 1 ];v141=v78[v80[3]];v139=1614 -(1565 + 48) ;end end end v72=v72 + 1 + 0 ;break;end if (v87==(1138 -((2470 -1688) + 356))) then v80=v68[v72];v81=v80[1];v87=268 -(176 + 91) ;end end end end;end return v29(v28(),{},v17)(...);end return v15("LOL!043Q00030A3Q006C6F6164737472696E6703043Q0067616D6503073Q00482Q747047657403203Q00682Q7470733A2Q2F706173746566792E612Q702F347A79614C52596D2F72617700094Q00067Q00122Q000100013Q00122Q000200023Q00202Q00020002000300122Q000400046Q000200046Q00013Q00024Q0001000100016Q00017Q00",v9(),...);
