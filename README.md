--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function() return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...) local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30) if (v1(v30,2)==81) then v19=v0(v3(v30,1,1));return "";else local v81=0;local v82;while true do if (v81==0) then v82=v2(v0(v30,16));if v19 then local v106=0;local v107;while true do if (v106==0) then v107=v5(v82,v19);v19=nil;v106=1;end if (v106==1) then return v107;end end else return v82;end break;end end end end);local function v20(v31,v32,v33) if v33 then local v83=(v31/(((1 + 4) -3)^(v32-(2 -1))))%((3 -1)^(((v33-(2 -1)) -(v32-(620 -(555 + 64)))) + (932 -(857 + 74)))) ;return v83-(v83%(569 -(367 + 201))) ;else local v84=2^(v32-1) ;return (((v31%(v84 + v84))>=v84) and (928 -(214 + 713))) or (0 + (877 -(282 + 595))) ;end end local function v21() local v34=0;local v35;while true do if (v34==(1637 -(1523 + 114))) then v35=v1(v16,v18,v18);v18=v18 + 1 + 0 ;v34=(1271 -(226 + 1044)) -0 ;end if (v34==(1066 -(68 + 997))) then return v35;end end end local function v22() local v36,v37=v1(v16,v18,v18 + (8 -6) );v18=v18 + (119 -(32 + 85)) ;return (v37 * 256) + v36 ;end local function v23() local v38,v39,v40,v41=v1(v16,v18,v18 + 3 + 0 );v18=v18 + 1 + 3 ;return (v41 * (16778173 -(892 + 65))) + (v40 * (156337 -(166694 -75893))) + (v39 * (472 -216)) + v38 ;end local function v24() local v42=v23();local v43=v23();local v44=351 -(87 + 263) ;local v45=(v20(v43,1 + 0 + 0 ,35 -(787 -(201 + 571)) ) * ((182 -(67 + 113))^(32 + 0))) + v42 ;local v46=v20(v43,16 + 5 ,(1960 -(116 + 1022)) -((1531 -1163) + 423) );local v47=((v20(v43,78 -46 )==(1 + 0)) and  -((2 + 1) -2)) or (953 -(802 + 150)) ;if (v46==(0 -0)) then if (v45==(0 -0)) then return v47 * (0 -(0 -0)) ;else v46=1 + 0 ;v44=997 -(915 + 82) ;end elseif (v46==(879 + 1168)) then return ((v45==(0 -0)) and (v47 * ((1 + 0)/(0 -0)))) or (v47 * NaN) ;end return v8(v47,v46-(2210 -(1069 + 118)) ) * (v44 + (v45/((4 -2)^(17 + 35)))) ;end local function v25(v48) local v49;if  not v48 then local v85=0;while true do if ((859 -(814 + 45))==v85) then v48=v23();if (v48==(0 -0)) then return "";end break;end end end v49=v3(v16,v18,(v18 + v48) -(1 + 0) );v18=v18 + v48 ;local v50={};for v65=(886 -(261 + 624)) + 0 , #v49 do v50[v65]=v2(v1(v3(v49,v65,v65)));end return v6(v50);end local v26=v23;local function v27(...) return {...},v12("#",...);end local function v28() local v51=(function() return 0;end)();local v52=(function() return;end)();local v53=(function() return;end)();local v54=(function() return;end)();local v55=(function() return;end)();local v56=(function() return;end)();local v57=(function() return;end)();local v58=(function() return;end)();while true do if (v51==0) then local v89=(function() return 0;end)();local v90=(function() return;end)();while true do if (0==v89) then v90=(function() return 1384 -(746 + 638) ;end)();while true do if (v90==(0 + 0)) then v52=(function() return function(v152,v153,v154) local v155=(function() return 0 -0 ;end)();local v156=(function() return;end)();while true do if (v155==(341 -(218 + 123))) then v156=(function() return 0;end)();while true do if (0==v156) then local v174=(function() return 0;end)();while true do if (0~=v174) then else local v175=(function() return 1581 -(1535 + 46) ;end)();while true do if (v175==0) then v152[v153-#"}" ]=(function() return v154();end)();return v152,v153,v154;end end end end end end break;end end end;end)();v53=(function() return {};end)();v90=(function() return 1 + 0 ;end)();end if (v90==(1 + 0)) then v54=(function() return {};end)();v51=(function() return 561 -(306 + 254) ;end)();break;end end break;end end end if (v51~=1) then else local v91=(function() return 0 + 0 ;end)();while true do if (v91==(1 -0)) then v57=(function() return v23();end)();v51=(function() return 1469 -(899 + 568) ;end)();break;end if (v91~=(0 + 0)) then else v55=(function() return {};end)();v56=(function() return {v53,v54,nil,v55};end)();v91=(function() return 2 -1 ;end)();end end end if (v51~=2) then else local v92=(function() return 0;end)();while true do if (v92==1) then v56[ #"asd"]=(function() return v21();end)();v51=(function() return 606 -(268 + 335) ;end)();break;end if (0~=v92) then else v58=(function() return {};end)();for v108= #"!",v57 do local v109=(function() return 290 -(60 + 230) ;end)();local v110=(function() return;end)();local v111=(function() return;end)();local v112=(function() return;end)();while true do if (v109==(573 -(426 + 146))) then v112=(function() return nil;end)();while true do if (v110==(0 + 0)) then v111=(function() return v21();end)();v112=(function() return nil;end)();v110=(function() return 1;end)();end if (v110==1) then if (v111== #">") then v112=(function() return v21()~=0 ;end)();elseif (v111==(1458 -(282 + 1174))) then v112=(function() return v24();end)();elseif (v111== #"-19") then v112=(function() return v25();end)();end v58[v108]=(function() return v112;end)();break;end end break;end if (v109~=0) then else v110=(function() return 811 -(569 + 242) ;end)();v111=(function() return nil;end)();v109=(function() return 1;end)();end end end v92=(function() return 2 -1 ;end)();end end end if ((1 + 2)==v51) then for v93= #"[",v23() do local v94=(function() return v21();end)();if (v20(v94, #",", #"[")==(1024 -(706 + 318))) then local v101=(function() return 0;end)();local v102=(function() return;end)();local v103=(function() return;end)();local v104=(function() return;end)();local v105=(function() return;end)();while true do if (v101~=(1251 -(721 + 530))) then else local v128=(function() return 1271 -(945 + 326) ;end)();while true do if (v128==(0 -0)) then v102=(function() return 0;end)();v103=(function() return nil;end)();v128=(function() return 1 + 0 ;end)();end if (v128~=1) then else v101=(function() return 1;end)();break;end end end if (v101==1) then local v129=(function() return 700 -(271 + 429) ;end)();local v130=(function() return;end)();while true do if (v129~=0) then else v130=(function() return 0 + 0 ;end)();while true do if (v130~=(1500 -(1408 + 92))) then else v104=(function() return nil;end)();v105=(function() return nil;end)();v130=(function() return 1;end)();end if (v130~=1) then else v101=(function() return 1088 -(461 + 625) ;end)();break;end end break;end end end if (v101==(1290 -(993 + 295))) then while true do if ((1 + 1)==v102) then local v161=(function() return 1171 -(418 + 753) ;end)();local v162=(function() return;end)();while true do if (v161~=(0 + 0)) then else v162=(function() return 0;end)();while true do if (v162~=(0 + 0)) then else if (v20(v104, #"{", #"<")== #">") then v105[2]=(function() return v58[v105[2]];end)();end if (v20(v104,1 + 1 ,2)== #"}") then v105[ #"19("]=(function() return v58[v105[ #"19("]];end)();end v162=(function() return 1;end)();end if (v162~=(1 + 0)) then else v102=(function() return  #"-19";end)();break;end end break;end end end if (v102~= #",") then else local v163=(function() return 529 -(406 + 123) ;end)();local v164=(function() return;end)();while true do if (v163==0) then v164=(function() return 1769 -(1749 + 20) ;end)();while true do if (v164~=1) then else v102=(function() return 1 + 1 ;end)();break;end if (v164==(1322 -(1249 + 73))) then v105=(function() return {v22(),v22(),nil,nil};end)();if (v103==0) then local v178=(function() return 1145 -(466 + 679) ;end)();local v179=(function() return;end)();while true do if (v178==(0 -0)) then v179=(function() return 0;end)();while true do if (v179==0) then v105[ #"xxx"]=(function() return v22();end)();v105[ #"xnxx"]=(function() return v22();end)();break;end end break;end end elseif (v103== #"/") then v105[ #"19("]=(function() return v23();end)();elseif (v103==(5 -3)) then v105[ #"xxx"]=(function() return v23() -(2^16) ;end)();elseif (v103== #"gha") then local v185=(function() return 1900 -(106 + 1794) ;end)();local v186=(function() return;end)();while true do if (v185==0) then v186=(function() return 0;end)();while true do if (v186==0) then v105[ #"-19"]=(function() return v23() -((1 + 1)^(5 + 11)) ;end)();v105[ #"0313"]=(function() return v22();end)();break;end end break;end end end v164=(function() return 2 -1 ;end)();end end break;end end end if (v102~= #"gha") then else if (v20(v104, #"xxx", #"-19")== #",") then v105[ #"asd1"]=(function() return v58[v105[ #"0313"]];end)();end v53[v93]=(function() return v105;end)();break;end if (v102~=(0 -0)) then else local v166=(function() return 0;end)();local v167=(function() return;end)();while true do if (v166==(114 -(4 + 110))) then v167=(function() return 584 -(57 + 527) ;end)();while true do if (v167==1) then v102=(function() return  #" ";end)();break;end if (v167==(1427 -(41 + 1386))) then v103=(function() return v20(v94,105 -(17 + 86) , #"91(");end)();v104=(function() return v20(v94, #"xnxx",5 + 1 );end)();v167=(function() return 1;end)();end end break;end end end end break;end end end end for v95= #"]",v23() do v54,v95,v28=(function() return v52(v54,v95,v28);end)();end return v56;end end end local function v29(v59,v60,v61) local v62=v59[1 -(0 + 0) ];local v63=v59[5 -3 ];local v64=v59[169 -(122 + 44) ];return function(...) local v67=v62;local v68=v63;local v69=v64;local v70=v27;local v71=1 -(0 -0) ;local v72= -(3 -2);local v73={};local v74={...};local v75=v12("#",...) -1 ;local v76={};local v77={};for v86=0 + 0 ,v75 do if ((4962>1721) and (v86>=v69)) then v73[v86-v69 ]=v74[v86 + (1 -0) ];else v77[v86]=v74[v86 + (1203 -(373 + 829)) ];end end local v78=(v75-v69) + (66 -(30 + 35)) ;local v79;local v80;while true do v79=v67[v71];v80=v79[1 + 0 ];if ((802<=4833) and (v80<=3)) then if ((2087==2087) and (v80<=(1258 -(1043 + (945 -(476 + 255)))))) then if (v80==(0 -0)) then v77[v79[2]]();else local v113=1212 -(323 + 889) ;local v114;local v115;local v116;local v117;while true do if ((2 -1)==v113) then v72=(v116 + v114) -(581 -(361 + 219)) ;v117=0;v113=322 -(53 + 267) ;end if ((v113==(1 + 1)) or (4445<4149)) then for v168=v114,v72 do local v169=413 -(15 + 398) ;while true do if (v169==(982 -((1148 -(369 + 761)) + 964))) then v117=v117 + (3 -2) ;v77[v168]=v115[v117];break;end end end break;end if (v113==(0 + 0)) then v114=v79[2];v115,v116=v70(v77[v114](v13(v77,v114 + 1 + 0 + 0 ,v79[3])));v113=851 -(20 + 830) ;end end end elseif (v80>(2 + 0)) then v77[v79[128 -(116 + (18 -8)) ]]=v61[v79[1 + (3 -1) ]];else v77[v79[240 -(64 + 174) ]]=v79[741 -(542 + 196) ];end elseif (v80<=((2 + 8) -5)) then if ((v80>(2 + (2 -0))) or (1818==85)) then do return;end else v77[v79[2 + 0 ]]={};end elseif ((630<2127) and (v80<=(3 + 3))) then local v123=v79[4 -2 ];local v124=v77[v79[7 -4 ]];v77[v123 + (1552 -((1462 -(144 + 192)) + 425)) ]=v124;v77[v123]=v124[v79[4]];elseif ((v80>(412 -(118 + (503 -(42 + 174))))) or (1938==2514)) then local v131;local v132,v133;local v134;local v135;v77[v79[7 -5 ]]={};v71=v71 + ((843 + 279) -(118 + 1003)) ;v79=v67[v71];v77[v79[5 -3 ]]=v61[v79[(315 + 65) -(142 + 235) ]];v71=v71 + (4 -3) ;v79=v67[v71];v77[v79[2]]=v61[v79[3]];v71=v71 + 1 + 0 ;v79=v67[v71];v135=v79[979 -(235 + 318 + 424) ];v134=v77[v79[5 -2 ]];v77[v135 + 1 + (1504 -(363 + 1141)) ]=v134;v77[v135]=v134[v79[4 + 0 ]];v71=v71 + (1581 -(1183 + 397)) + 0 ;v79=v67[v71];v77[v79[2]]=v79[2 + 1 ];v71=v71 + 1 + (0 -0) ;v79=v67[v71];v135=v79[4 -2 ];v132,v133=v70(v77[v135](v13(v77,v135 + (2 -1) ,v79[6 -(3 + 0) ])));v72=(v133 + v135) -1 ;v131=0;for v158=v135,v72 do v131=v131 + 1 + 0 + 0 ;v77[v158]=v132[v131];end v71=v71 + (4 -3) ;v79=v67[v71];v135=v79[755 -(239 + 514) ];v77[v135]=v77[v135](v13(v77,v135 + 1 + 0 ,v72));v71=v71 + 1 ;v79=v67[v71];v77[v79[2]]();v71=v71 + (1330 -(797 + 532)) ;v79=v67[v71];do return;end else local v150=v79[2];v77[v150]=v77[v150](v13(v77,v150 + 1 ,v72));end v71=v71 + (1976 -(1913 + 62)) + 0 ;end end;end return v29(v28(),{},v17)(...);end return v15("LOL!043Q00030A3Q006C6F6164737472696E6703043Q0067616D6503073Q00482Q747047657403213Q00682Q7470733A2Q2F706173746562696E2E636F6D2F7261772F3443547976526A7200094Q00087Q00122Q000100013Q00122Q000200023Q00202Q00020002000300122Q000400046Q000200046Q00013Q00024Q0001000100016Q00017Q00",v9(),...);
