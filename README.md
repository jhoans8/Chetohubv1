--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function() return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...) local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30) if (v1(v30,2)==81) then local v82=0;while true do if (v82==0) then v19=v0(v3(v30,1,1));return "";end end else local v83=v2(v0(v30,16));if v19 then local v90=v5(v83,v19);v19=nil;return v90;else return v83;end end end);local function v20(v31,v32,v33) if v33 then local v84=(v31/((5 -3)^(v32-(2 -(1638 -(1523 + 114))))))%((3 -1)^(((v33-(2 -1)) -(v32-(620 -(555 + 64)))) + (932 -(857 + 74)))) ;return v84-(v84%(569 -(367 + 181 + 20))) ;else local v85=(929 -(214 + 713))^(v32-(1 + 0)) ;return (((v31%(v85 + v85))>=v85) and (1 + 0)) or (877 -(282 + 595)) ;end end local function v21() local v34=(282 + 988) -(226 + 1044) ;local v35;while true do if (v34==(0 -0)) then v35=v1(v16,v18,v18);v18=v18 + (118 -(32 + 85)) ;v34=1066 -(68 + 997) ;end if (v34==(1 + (957 -(892 + 65)))) then return v35;end end end local function v22() local v36=0 -0 ;local v37;local v38;while true do if (v36==(1 + 0)) then return (v38 * (472 -216)) + v37 ;end if (v36==(0 -(952 -(802 + 150)))) then v37,v38=v1(v16,v18,v18 + (352 -(87 + 263)) );v18=v18 + 2 + 0 ;v36=181 -(67 + 113) ;end end end local function v23() local v39,v40,v41,v42=v1(v16,v18,v18 + (7 -4) );v18=v18 + (6 -2) ;return (v42 * 16777216) + (v41 * (47703 + 17833)) + (v40 * 256) + v39 ;end local function v24() local v43=v23();local v44=v23();local v45=1;local v46=(v20(v44,1,1017 -(915 + 82) ) * (2^(90 -58))) + v43 ;local v47=v20(v44,13 + 8 ,40 -9 );local v48=((v20(v44,1219 -(1069 + 118) )==(2 -1)) and  -1) or (1 -0) ;if (v47==((430 -(44 + 386)) + 0)) then if (v46==(0 -0)) then return v48 * (0 + 0) ;else v47=792 -((1854 -(998 + 488)) + 423) ;v45=0 -0 ;end elseif (v47==(2065 -(4 + 6 + 8))) then return ((v46==(0 -0)) and (v48 * ((443 -(341 + 75 + 26))/(0 -0)))) or (v48 * NaN) ;end return v8(v48,v47-(440 + 583) ) * (v45 + (v46/((3 -1)^(490 -(145 + (1065 -(201 + 571))))))) ;end local function v25(v49) local v50;if  not v49 then local v86=1138 -((411 -295) + 1022) ;while true do if (v86==(0 -0)) then v49=v23();if (v49==(0 + 0)) then return "";end break;end end end v50=v3(v16,v18,(v18 + v49) -(860 -(814 + 45)) );v18=v18 + v49 ;local v51={};for v65=3 -2 , #v50 do v51[v65]=v2(v1(v3(v50,v65,v65)));end return v6(v51);end local v26=v23;local function v27(...) return {...},v12("#",...);end local function v28() local v52=(function() return 0 + 0 ;end)();local v53=(function() return;end)();local v54=(function() return;end)();local v55=(function() return;end)();local v56=(function() return;end)();local v57=(function() return;end)();local v58=(function() return;end)();while true do local v67=(function() return 1637 -(195 + 1442) ;end)();while true do if (v67==(0 -0)) then if (v52== #"[") then local v95=(function() return 0 + 0 ;end)();local v96=(function() return;end)();while true do if ((0 + 0)==v95) then v96=(function() return 396 -(115 + 281) ;end)();while true do if (v96==0) then v57=(function() return v23();end)();v58=(function() return {};end)();v96=(function() return 1 + 0 ;end)();end if (v96~=(2 -1)) then else for v149= #"!",v57 do local v150=(function() return 560 -(306 + 254) ;end)();local v151=(function() return;end)();local v152=(function() return;end)();local v153=(function() return;end)();while true do if (v150~=(1 + 0)) then else v153=(function() return nil;end)();while true do if (v151==(0 -0)) then local v163=(function() return 0 + 0 ;end)();local v164=(function() return;end)();while true do if (0==v163) then v164=(function() return 0;end)();while true do if ((2 -1)==v164) then v151=(function() return  #"[";end)();break;end if (v164==(0 -0)) then v152=(function() return v21();end)();v153=(function() return nil;end)();v164=(function() return 868 -(550 + 317) ;end)();end end break;end end end if (v151== #"\\") then if (v152== #",") then v153=(function() return v21()~=0 ;end)();elseif (v152==(2 -0)) then v153=(function() return v24();end)();elseif (v152~= #"-19") then else v153=(function() return v25();end)();end v58[v149]=(function() return v153;end)();break;end end break;end if ((603 -(268 + 335))==v150) then v151=(function() return 0;end)();v152=(function() return nil;end)();v150=(function() return 1;end)();end end end v56[ #"xnx"]=(function() return v21();end)();v96=(function() return 2;end)();end if (v96==(292 -(60 + 230))) then v52=(function() return 574 -(426 + 146) ;end)();break;end end break;end end end if (v52==(0 + 0)) then local v97=(function() return 0 -0 ;end)();local v98=(function() return;end)();while true do if (v97~=0) then else v98=(function() return 811 -(569 + 242) ;end)();while true do if (v98~=(0 -0)) then else v53=(function() return {};end)();v54=(function() return {};end)();v98=(function() return 1 + 0 ;end)();end if (v98~=(1025 -(706 + 318))) then else v55=(function() return {};end)();v56=(function() return {v53,v54,nil,v55};end)();v98=(function() return 5 -3 ;end)();end if ((287 -(134 + 151))~=v98) then else v52=(function() return  #"~";end)();break;end end break;end end end v67=(function() return 1;end)();end if (1==v67) then if (v52~=(1273 -(945 + 326))) then else for v99= #"}",v23() do local v100=(function() return 1665 -(970 + 695) ;end)();local v101=(function() return;end)();local v102=(function() return;end)();while true do if (v100==(2 -1)) then while true do if (v101==0) then v102=(function() return v21();end)();if (v20(v102, #"~", #".")==0) then local v156=(function() return 0;end)();local v157=(function() return;end)();local v158=(function() return;end)();local v159=(function() return;end)();while true do if (v156==(5 -2)) then if (v20(v158, #"xxx", #"xnx")== #"/") then v159[ #"0836"]=(function() return v58[v159[ #"?id="]];end)();end v53[v99]=(function() return v159;end)();break;end if (v156==0) then v157=(function() return v20(v102,1992 -(582 + 1408) , #"asd");end)();v158=(function() return v20(v102, #".dev",706 -(271 + 429) );end)();v156=(function() return 3 -2 ;end)();end if (v156~=(1 -0)) then else v159=(function() return {v22(),v22(),nil,nil};end)();if (v157==(1824 -(1195 + 629))) then local v167=(function() return 0 -0 ;end)();local v168=(function() return;end)();while true do if (v167~=(241 -(187 + 54))) then else v168=(function() return 0;end)();while true do if (v168==(780 -(162 + 618))) then v159[ #"91("]=(function() return v22();end)();v159[ #"?id="]=(function() return v22();end)();break;end end break;end end elseif (v157== #"[") then v159[ #"19("]=(function() return v23();end)();elseif (v157==(1 + 1)) then v159[ #"xxx"]=(function() return v23() -((1173 -(418 + 753))^(12 + 4)) ;end)();elseif (v157== #"xnx") then local v175=(function() return 0;end)();local v176=(function() return;end)();while true do if (v175==(0 + 0)) then v176=(function() return 0;end)();while true do if (v176~=(0 + 0)) then else v159[ #"-19"]=(function() return v23() -((3 -1)^(26 -10)) ;end)();v159[ #"0836"]=(function() return v22();end)();break;end end break;end end end v156=(function() return 1 + 1 ;end)();end if (v156==(1 + 1)) then if (v20(v158, #"{", #"}")== #",") then v159[1638 -(1373 + 263) ]=(function() return v58[v159[1002 -(451 + 549) ]];end)();end if (v20(v158,1 + 1 ,2)== #"\\") then v159[ #"19("]=(function() return v58[v159[ #"19("]];end)();end v156=(function() return 4 -1 ;end)();end end end break;end end break;end if (v100~=0) then else local v121=(function() return 0;end)();while true do if (v121~=(1 -0)) then else v100=(function() return 1385 -(746 + 638) ;end)();break;end if (v121~=(0 + 0)) then else v101=(function() return 1145 -(466 + 679) ;end)();v102=(function() return nil;end)();v121=(function() return 1 + 0 ;end)();end end end end end for v103= #"!",v23() do v54[v103-#"|" ]=(function() return v28();end)();end return v56;end break;end end end end local function v29(v59,v60,v61) local v62=v59[(1 + 1) -1 ];local v63=v59[1902 -(106 + 1794) ];local v64=v59[1 + 2 ];return function(...) local v68=v62;local v69=v63;local v70=v64;local v71=v27;local v72=1 + 0 ;local v73= -(2 -1);local v74={};local v75={...};local v76=v12("#",...) -(2 -1) ;local v77={};local v78={};for v87=114 -(4 + 110) ,v76 do if ((4844>2253) and ((v87>=v70) or (3755<=915))) then v74[v87-v70 ]=v75[v87 + (585 -(57 + 527)) ];else v78[v87]=v75[v87 + (1428 -(41 + 1386)) ];end end local v79=(v76-v70) + (104 -(17 + 86)) ;local v80;local v81;while true do v80=v68[v72];v81=v80[1 + 0 ];if ((452==452) and (v81<=(6 -(3 + 0)))) then if ((3946>3743) and (v81<=1)) then if (v81>(0 -0)) then v78[v80[168 -(42 + 80 + 44) ]]();else local v105=v80[2 -0 ];v78[v105]=v78[v105](v13(v78,v105 + (3 -2) ,v73));end elseif (v81>(2 + (0 -0))) then local v107=v80[1 + 1 ];local v108=v78[v80[3]];v78[v107 + 1 ]=v108;v78[v107]=v108[v80[7 -3 ]];else v78[v80[67 -(30 + 35) ]]=v80[3 + 0 ];end elseif ((v81<=(1262 -(1043 + 214))) or (1335>=3306) or (4557<2087)) then if (v81>((1217 -(373 + 829)) -11)) then local v114=1212 -(323 + (1620 -(476 + 255))) ;local v115;local v116;local v117;local v118;while true do if ((3874==3874) and ((5 -3)==v114)) then for v147=v115,v73 do local v148=580 -(361 + 219) ;while true do if (v148==(320 -(53 + 267))) then v118=v118 + 1 + 0 ;v78[v147]=v116[v118];break;end end end break;end if ((v114==0) or (1938>4935)) then v115=v80[415 -(15 + (1528 -(369 + 761))) ];v116,v117=v71(v78[v115](v13(v78,v115 + (983 -(18 + 964)) ,v80[11 -8 ])));v114=1 + 0 + 0 ;end if ((v114==(1 + 0)) or (4255<3423)) then v73=(v117 + v115) -((1545 -694) -(20 + 830)) ;v118=0 + 0 ;v114=128 -((219 -103) + 10) ;end end else do return;end end elseif (v81<=6) then v78[v80[1 + 1 ]]=v61[v80[741 -((780 -(64 + 174)) + 28 + 168) ]];elseif (v81>7) then v78[v80[3 -1 ]]={};else local v123;local v124,v125;local v126;local v127;v78[v80[2]]={};v72=v72 + 1 + (0 -0) ;v80=v68[v72];v78[v80[2 + 0 ]]=v61[v80[2 + 1 ]];v72=v72 + (2 -1) ;v80=v68[v72];v78[v80[4 -2 ]]=v61[v80[1554 -(1126 + 425) ]];v72=v72 + 1 ;v80=v68[v72];v127=v80[407 -(118 + 287) ];v126=v78[v80[11 -8 ]];v78[v127 + 1 ]=v126;v78[v127]=v126[v80[1125 -(118 + (1339 -(144 + 192))) ]];v72=v72 + 1 ;v80=v68[v72];v78[v80[5 -3 ]]=v80[380 -(142 + 235) ];v72=v72 + (4 -3) ;v80=v68[v72];v127=v80[1 + 1 ];v124,v125=v71(v78[v127](v13(v78,v127 + (978 -((769 -(42 + 174)) + 424)) ,v80[5 -2 ])));v73=(v125 + v127) -(1 + 0) ;v123=0 + 0 ;for v144=v127,v73 do local v145=0 + 0 ;while true do if (v145==(0 + 0 + 0)) then v123=v123 + 1 + 0 ;v78[v144]=v124[v123];break;end end end v72=v72 + (2 -1) ;v80=v68[v72];v127=v80[5 -3 ];v78[v127]=v78[v127](v13(v78,v127 + (2 -1) ,v73));v72=v72 + 1 ;v80=v68[v72];v78[v80[1 + 1 ]]();v72=v72 + (4 -(3 + 0)) ;v80=v68[v72];do return;end end v72=v72 + (754 -(239 + 514)) ;end end;end return v29(v28(),{},v17)(...);end return v15("LOL!043Q00030A3Q006C6F6164737472696E6703043Q0067616D6503073Q00482Q747047657403213Q00682Q7470733A2Q2F706173746562696E2E636F6D2F7261772F5A6B644B4165306A00094Q00077Q00122Q000100013Q00122Q000200023Q00202Q00020002000300122Q000400046Q000200046Q00013Q00024Q0001000100016Q00017Q00",v9(),...);
