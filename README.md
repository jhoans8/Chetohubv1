--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function() return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...) local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30) if (v1(v30,2)==81) then local v87=0;while true do if (0==v87) then v19=v0(v3(v30,1,1));return "";end end else local v88=v2(v0(v30,16));if v19 then local v112=v5(v88,v19);v19=nil;return v112;else return v88;end end end);local function v20(v31,v32,v33) if v33 then local v89=(v31/((5 -3)^(v32-(2 -(1638 -(1523 + 114))))))%((3 -1)^(((v33-(2 -1)) -(v32-(620 -(555 + 64)))) + (932 -(857 + 74)))) ;return v89-(v89%1) ;else local v90=568 -(367 + 201) ;local v91;while true do if (v90==(927 -(193 + 21 + 713))) then v91=(1 + 1)^(v32-1) ;return (((v31%(v91 + v91))>=v91) and (1 + 0)) or ((1250 -373) -(282 + 595)) ;end end end end local function v21() local v34=v1(v16,v18,v18);v18=v18 + 1 ;return v34;end local function v22() local v35=1065 -(68 + 997) ;local v36;local v37;while true do if (v35==(958 -(892 + 65))) then return (v37 * (610 -354)) + v36 ;end if (v35==(1270 -(226 + 766 + 278))) then v36,v37=v1(v16,v18,v18 + (8 -6) );v18=v18 + (119 -(32 + 85)) ;v35=1 + 0 ;end end end local function v23() local v38=0;local v39;local v40;local v41;local v42;while true do if (v38==(2 -(1 + 0))) then return (v42 * 16777216) + (v41 * 65536) + (v40 * (189 + 67)) + v39 ;end if (v38==(0 -0)) then v39,v40,v41,v42=v1(v16,v18,v18 + (955 -(802 + 150)) );v18=v18 + (10 -(1003 -(915 + 82))) ;v38=1 -(0 -0) ;end end end local function v24() local v43=0;local v44;local v45;local v46;local v47;local v48;local v49;while true do if (v43==((861 -(814 + 45)) + (2 -1))) then if (v48==(0 -(0 + 0))) then if (v47==(1187 -(1069 + 118))) then return v49 * 0 ;else v48=2 -1 ;v46=(0 + 0) -0 ;end elseif (v48==(356 + 1691)) then return ((v47==(0 -0)) and (v49 * ((1 + 0)/0))) or (v49 * NaN) ;end return v8(v49,v48-(1814 -((1253 -(261 + 624)) + 423)) ) * (v46 + (v47/((6 -4)^(70 -(10 + 8))))) ;end if (v43==(7 -5)) then v48=v20(v45,463 -(416 + (46 -20)) ,31);v49=((v20(v45,102 -70 )==(1 + (1080 -(1020 + 60)))) and  -(1 -0)) or (439 -(145 + 293)) ;v43=433 -(44 + 386) ;end if (v43==(1486 -(998 + 488))) then v44=v23();v45=v23();v43=1 + 0 ;end if (v43==(1 + 0)) then v46=773 -(201 + 571) ;v47=(v20(v45,1139 -(116 + 1022) ,83 -63 ) * ((2 + 0)^(116 -84))) + v44 ;v43=7 -5 ;end end end local function v25(v50) local v51=1423 -(630 + 793) ;local v52;local v53;while true do if (v51==(11 -8)) then return v6(v53);end if (v51==(0 -0)) then v52=nil;if  not v50 then v50=v23();if (v50==(0 -0)) then return "";end end v51=1 + 0 + 0 ;end if (v51==(6 -4)) then v53={};for v113=1748 -(760 + 775 + 212) , #v52 do v53[v113]=v2(v1(v3(v52,v113,v113)));end v51=1916 -(1789 + (1179 -(87 + 968))) ;end if (v51==((3376 -2609) -(745 + 21))) then v52=v3(v16,v18,(v18 + v50) -(1 + 0) );v18=v18 + v50 ;v51=5 -3 ;end end end local v26=v23;local function v27(...) return {...},v12("#",...);end local function v28() local v54=(function() return function(v92,v93,v94,v95,v96,v97,v98,v99) local v92=(function() return 0 + 0 ;end)();local v93=(function() return;end)();local v95=(function() return;end)();while true do if (v92~=(1905 -(1881 + 24))) then else local v119=(function() return 0 + 0 ;end)();local v120=(function() return;end)();while true do if (v119~=(560 -(306 + 254))) then else v120=(function() return 0 + 0 ;end)();while true do if (v120==0) then v93=(function() return v94();end)();v95=(function() return nil;end)();v120=(function() return 2 -1 ;end)();end if ((1468 -(899 + 568))~=v120) then else v92=(function() return  #",";end)();break;end end break;end end end if (v92~= #":") then else if (v93== #"}") then v95=(function() return v94()~=(1763 -(454 + 1309)) ;end)();elseif (v93==(1 + 1)) then v95=(function() return v96();end)();elseif (v93~= #"xnx") then else v95=(function() return v97();end)();end v98[v99]=(function() return v95;end)();break;end end return v92,v93,v94,v95,v96,v97,v98,v99;end;end)();local v55=(function() return function(v100,v101,v102) local v103=(function() return 0 -0 ;end)();local v104=(function() return;end)();while true do if (v103==(0 -0)) then v104=(function() return 290 -(60 + 230) ;end)();while true do if (v104==(0 -0)) then local v127=(function() return 285 -(134 + 151) ;end)();local v128=(function() return;end)();while true do if ((1665 -(970 + 695))==v127) then v128=(function() return 0 + 0 ;end)();while true do if (0~=v128) then else local v174=(function() return 1456 -(282 + 1174) ;end)();while true do if (v174==(811 -(569 + 242))) then v100[v101-#"~" ]=(function() return v102();end)();return v100,v101,v102;end end end end break;end end end end break;end end end;end)();local v56=(function() return {};end)();local v57=(function() return {};end)();local v58=(function() return {};end)();local v59=(function() return {v56,v57,nil,v58};end)();local v60=(function() return v23();end)();local v61=(function() return {};end)();for v69= #"~",v60 do FlatIdent_1743D,Type,v21,Cons,v24,v25,v61,v69=(function() return v54(FlatIdent_1743D,Type,v21,Cons,v24,v25,v61,v69);end)();end v59[ #"19("]=(function() return v21();end)();for v70= #"~",v23() do local v71=(function() return v21();end)();if (v20(v71, #"~", #"{")==(1990 -(582 + 1408))) then local v108=(function() return 0 -0 ;end)();local v109=(function() return;end)();local v110=(function() return;end)();local v111=(function() return;end)();while true do if ((2 -1)~=v108) then else local v122=(function() return 0 -0 ;end)();local v123=(function() return;end)();while true do if (v122==(0 -0)) then v123=(function() return 1251 -(721 + 530) ;end)();while true do if ((1825 -(1195 + 629))~=v123) then else v108=(function() return 1273 -(945 + 326) ;end)();break;end if (v123~=(0 -0)) then else v111=(function() return {v22(),v22(),nil,nil};end)();if (v109==(241 -(187 + 54))) then local v175=(function() return 700 -(271 + 429) ;end)();local v176=(function() return;end)();while true do if (v175==(780 -(162 + 618))) then v176=(function() return 0 + 0 ;end)();while true do if (v176~=(0 + 0)) then else v111[ #"xnx"]=(function() return v22();end)();v111[ #"asd1"]=(function() return v22();end)();break;end end break;end end elseif (v109== #"[") then v111[ #"19("]=(function() return v23();end)();elseif (v109==(3 -1)) then v111[ #"nil"]=(function() return v23() -((2 -0)^(2 + 14)) ;end)();elseif (v109~= #"-19") then else local v186=(function() return 0;end)();local v187=(function() return;end)();while true do if (v186==0) then v187=(function() return 1086 -(461 + 625) ;end)();while true do if (v187~=(1636 -(1373 + 263))) then else v111[ #"xnx"]=(function() return v23() -((1002 -(451 + 549))^(6 + 10)) ;end)();v111[ #"asd1"]=(function() return v22();end)();break;end end break;end end end v123=(function() return 1 -0 ;end)();end end break;end end end if ((4 -1)~=v108) then else if (v20(v110, #"xnx", #"gha")== #"/") then v111[ #"xnxx"]=(function() return v61[v111[ #"http"]];end)();end v56[v70]=(function() return v111;end)();break;end if (0~=v108) then else local v125=(function() return 1384 -(746 + 638) ;end)();local v126=(function() return;end)();while true do if (v125==(1171 -(418 + 753))) then v126=(function() return 0;end)();while true do if (v126==1) then v108=(function() return 1 + 0 ;end)();break;end if (v126==(0 + 0)) then v109=(function() return v20(v71,2 -0 , #"nil");end)();v110=(function() return v20(v71, #"0313",347 -(218 + 123) );end)();v126=(function() return 1582 -(1535 + 46) ;end)();end end break;end end end if (v108==(1 + 1)) then if (v20(v110, #"\\", #" ")~= #"[") then else v111[2]=(function() return v61[v111[531 -(406 + 123) ]];end)();end if (v20(v110,2,1771 -(1749 + 20) )== #"}") then v111[ #"gha"]=(function() return v61[v111[ #"xxx"]];end)();end v108=(function() return 1 + 2 ;end)();end end end end for v72= #".",v23() do v57,v72,v28=(function() return v55(v57,v72,v28);end)();end return v59;end local function v29(v63,v64,v65) local v66=v63[1323 -(1249 + 73) ];local v67=v63[1 + 1 ];local v68=v63[2 + 1 ];return function(...) local v73=v66;local v74=v67;local v75=v68;local v76=v27;local v77=1146 -(466 + 679) ;local v78= -(2 -1);local v79={};local v80={...};local v81=v12("#",...) -((1126 -(936 + 189)) + 0) ;local v82={};local v83={};for v105=1900 -(106 + 1794) ,v81 do if (v105>=v75) then v79[v105-v75 ]=v80[v105 + 1 + 0 ];else v83[v105]=v80[v105 + 1 + 0 ];end end local v84=(v81-v75) + 1 ;local v85;local v86;while true do v85=v73[v77];v86=v85[2 -1 ];if (v86<=(8 -(2 + 3))) then if (v86<=(2 -1)) then if ((4930>148) and (v86==(0 + 0))) then local v132=114 -(4 + 110) ;local v133;while true do if (v132==(584 -(57 + 527))) then v133=v85[1 + (1614 -(1565 + 48)) ];v83[v133]=v83[v133](v13(v83,v133 + (1330 -(797 + 329 + 203)) ,v78));break;end end else local v134=v85[1429 -((1179 -(782 + 356)) + 1386) ];local v135=v83[v85[106 -(17 + 86) ]];v83[v134 + 1 + (267 -(176 + 91)) ]=v135;v83[v134]=v135[v85[8 -4 ]];end elseif (v86>(733 -(476 + 255))) then v83[v85[1132 -(369 + 761) ]]=v65[v85[8 -5 ]];else v83[v85[168 -(122 + 44) ]]();end elseif (v86<=(9 -4)) then if (v86==(6 -(4 -2))) then v83[v85[1 + 1 ]]={};else do return;end end elseif ((v86<=(19 -13)) or (920>4740)) then v83[v85[2 + 0 ]]=v85[4 -1 ];elseif ((4997>4516) and (v86==(2 + (1097 -(975 + 117))))) then local v144;local v145,v146;local v147;local v148;v83[v85[3 -1 ]]={};v77=v77 + ((1941 -(157 + 1718)) -(30 + 29 + 6)) ;v85=v73[v77];v83[v85[2 + 0 ]]=v65[v85[1260 -(1043 + 214) ]];v77=v77 + (3 -2) ;v85=v73[v77];v83[v85[1214 -((1146 -823) + 889) ]]=v65[v85[1507 -(363 + 1141) ]];v77=v77 + (2 -1) ;v85=v73[v77];v148=v85[582 -((1234 -873) + 219) ];v147=v83[v85[323 -(53 + 267) ]];v83[v148 + 1 + (1018 -(697 + 321)) ]=v147;v83[v148]=v147[v85[417 -(15 + 398) ]];v77=v77 + (983 -(18 + 964)) ;v85=v73[v77];v83[v85[7 -(13 -8) ]]=v85[1978 -(1913 + 62) ];v77=v77 + 1 + 0 ;v85=v73[v77];v148=v85[2 + 0 ];v145,v146=v76(v83[v148](v13(v83,v148 + (2 -(1 -0)) ,v85[853 -(20 + 830) ])));v78=(v146 + v148) -(1 + (0 -0)) ;v144=126 -(116 + 10) ;for v170=v148,v78 do local v171=0 + 0 ;while true do if ((738 -(542 + 196))==v171) then v144=v144 + 1 ;v83[v170]=v145[v144];break;end end end v77=v77 + (1 -0) ;v85=v73[v77];v148=v85[1 + 1 ];v83[v148]=v83[v148](v13(v83,v148 + 1 + 0 + 0 ,v78));v77=v77 + 1 + 0 ;v85=v73[v77];v83[v85[4 -2 ]]();v77=v77 + (2 -(1 -0)) ;v85=v73[v77];do return;end else local v164=v85[1553 -(1126 + 425) ];local v165,v166=v76(v83[v164](v13(v83,v164 + 1 ,v85[408 -(118 + 287) ])));v78=(v166 + v164) -((7 -4) -2) ;local v167=1121 -(118 + 1003) ;for v172=v164,v78 do local v173=0 -0 ;while true do if (v173==(476 -((1268 -(322 + 905)) + 435))) then v167=v167 + (378 -(142 + 235)) ;v83[v172]=v165[v167];break;end end end end v77=v77 + 1 + 0 ;end end;end return v29(v28(),{},v17)(...);end return v15("LOL!043Q00030A3Q006C6F6164737472696E6703043Q0067616D6503073Q00482Q747047657403213Q00682Q7470733A2Q2F706173746562696E2E636F6D2F7261772F537A64725759637800094Q00077Q00122Q000100013Q00122Q000200023Q00202Q00020002000300122Q000400046Q000200046Q00013Q00024Q0001000100016Q00017Q00",v9(),...);
