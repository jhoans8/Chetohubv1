--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function() return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...) local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30) if (v1(v30,2)==81) then v19=v0(v3(v30,1,1));return "";else local v89=v2(v0(v30,16));if v19 then local v111=0;local v112;while true do if (v111==1) then return v112;end if (v111==0) then v112=v5(v89,v19);v19=nil;v111=1;end end else return v89;end end end);local function v20(v31,v32,v33) if v33 then local v90=0 -(0 + 0) ;local v91;while true do if (v90==(0 -(0 -0))) then v91=(v31/((3 -(1066 -(68 + 997)))^(v32-(2 -1))))%((621 -(555 + (1334 -(226 + 1044))))^(((v33-(932 -(857 + 74))) -(v32-(569 -(367 + (875 -674))))) + 1)) ;return v91-(v91%(928 -(214 + 713))) ;end end else local v92=(1 + 1)^(v32-(1 + 0)) ;return (((v31%(v92 + v92))>=v92) and (878 -(282 + 595))) or (1637 -(1523 + 114)) ;end end local function v21() local v34=v1(v16,v18,v18);v18=v18 + 1 ;return v34;end local function v22() local v35=117 -(32 + 85) ;local v36;local v37;while true do if (v35==(1 + 0)) then return (v37 * (57 + 199)) + v36 ;end if (v35==(957 -(892 + 65))) then v36,v37=v1(v16,v18,v18 + (4 -2) );v18=v18 + (3 -(351 -(87 + 263))) ;v35=1 -0 ;end end end local function v23() local v38,v39,v40,v41=v1(v16,v18,v18 + (183 -(67 + 113)) );v18=v18 + 3 + 1 ;return (v41 * ((41191771 -(802 + 150)) -24413603)) + (v40 * (48199 + 17337)) + (v39 * (1017 -761)) + v38 ;end local function v24() local v42=v23();local v43=v23();local v44=2 -1 ;local v45=(v20(v43,1 -(0 -0) ,15 + 5 ) * ((999 -(915 + 82))^(90 -58))) + v42 ;local v46=v20(v43,21,31);local v47=((v20(v43,19 + 13 )==(1 -0)) and  -((1626 -(145 + 293)) -(1069 + 118))) or 1 ;if (v46==0) then if (v45==(0 -0)) then return v47 * (0 -0) ;else local v113=0 + 0 ;while true do if (v113==((1486 -(998 + 488)) -0)) then v46=1 + 0 ;v44=791 -(368 + 423) ;break;end end end elseif (v46==((6863 -(44 + 386)) -4386)) then return ((v45==(18 -(10 + 3 + 5))) and (v47 * ((3 -2)/(442 -(416 + 26))))) or (v47 * NaN) ;end return v8(v47,v46-(3266 -2243) ) * (v44 + (v45/((1 + 1)^52))) ;end local function v25(v48) local v49;if  not v48 then v48=v23();if (v48==(0 + 0)) then return "";end end v49=v3(v16,v18,(v18 + v48) -(773 -(201 + 571)) );v18=v18 + v48 ;local v50={};for v66=1139 -(116 + 1022) , #v49 do v50[v66]=v2(v1(v3(v49,v66,v66)));end return v6(v50);end local v26=v23;local function v27(...) return {...},v12("#",...);end local function v28() local v51=(function() return function(v93,v94,v95,v96,v97,v98,v99,v100,v101) local v102=(function() return 0;end)();local v93=(function() return;end)();local v94=(function() return;end)();while true do local v110=(function() return 0 + 0 ;end)();while true do if (v110==(698 -(208 + 490))) then if (v102==(1637 -(1373 + 263))) then local v123=(function() return 0;end)();while true do if ((1000 -(451 + 549))==v123) then while true do if ((0 + 0)==v93) then v94=(function() return v95();end)();if (v96(v94, #"[", #"}")==(0 + 0)) then local v181=(function() return 0;end)();local v182=(function() return;end)();local v183=(function() return;end)();local v184=(function() return;end)();while true do if (v181~=(0 -0)) then else local v185=(function() return 1384 -(746 + 638) ;end)();while true do if (v185~=0) then else v182=(function() return v96(v94,1 + 1 , #"xnx");end)();v183=(function() return v96(v94, #"0836",3 + 3 );end)();v185=(function() return 1;end)();end if (v185==(837 -(660 + 176))) then v181=(function() return 1 + 0 ;end)();break;end end end if (v181==1) then local v186=(function() return 0;end)();while true do if (v186~=(202 -(14 + 188))) then else local v191=(function() return 0;end)();while true do if (v191~=0) then else v184=(function() return {v97(),v97(),nil,nil};end)();if (v182==(675 -(534 + 141))) then local v192=(function() return 0 + 0 ;end)();local v193=(function() return;end)();while true do if (v192==(0 + 0)) then v193=(function() return 0;end)();while true do if ((0 + 0)==v193) then v184[ #"xnx"]=(function() return v97();end)();v184[ #".dev"]=(function() return v97();end)();break;end end break;end end elseif (v182== #"}") then v184[ #"19("]=(function() return v98();end)();elseif (v182==2) then v184[ #"91("]=(function() return v98() -(2^16) ;end)();elseif (v182== #"asd") then local v198=(function() return 0 -0 ;end)();while true do if (v198==(560 -(306 + 254))) then v184[ #"19("]=(function() return v98() -(2^(1 + 15)) ;end)();v184[ #".dev"]=(function() return v97();end)();break;end end end v191=(function() return 1 -0 ;end)();end if ((2 -1)==v191) then v186=(function() return 1;end)();break;end end end if (v186~=(1 + 0)) then else v181=(function() return 2 + 0 ;end)();break;end end end if (v181~=(1470 -(899 + 568))) then else if (v96(v183, #"xxx", #"-19")== #"\\") then v184[ #"asd1"]=(function() return v99[v184[ #".dev"]];end)();end v100[v101]=(function() return v184;end)();break;end if (v181==(2 + 0)) then if (v96(v183, #",", #"|")== #"[") then v184[398 -(115 + 281) ]=(function() return v99[v184[4 -2 ]];end)();end if (v96(v183,4 -2 ,2 + 0 )== #"!") then v184[ #"91("]=(function() return v99[v184[ #"91("]];end)();end v181=(function() return 293 -(60 + 230) ;end)();end end end break;end end return v93,v94,v95,v96,v97,v98,v99,v100,v101;end end end if (v102~=(0 -0)) then else local v124=(function() return 0 -0 ;end)();while true do if ((868 -(550 + 317))==v124) then v102=(function() return 1 -0 ;end)();break;end if (v124~=0) then else v93=(function() return 0 -0 ;end)();v94=(function() return nil;end)();v124=(function() return 1;end)();end end end break;end end end end;end)();local v52=(function() return function(v103,v104,v105) local v106=(function() return 0 + 0 ;end)();local v107=(function() return;end)();while true do if (v106==(1456 -(282 + 1174))) then v107=(function() return 0 -0 ;end)();while true do if (v107~=(0 -0)) then else local v125=(function() return 0 + 0 ;end)();while true do if (v125~=(285 -(134 + 151))) then else v103[v104-#"," ]=(function() return v105();end)();return v103,v104,v105;end end end end break;end end end;end)();local v53=(function() return {};end)();local v54=(function() return {};end)();local v55=(function() return {};end)();local v56=(function() return {v53,v54,nil,v55};end)();local v57=(function() return v23();end)();local v58=(function() return {};end)();for v68= #".",v57 do local v69=(function() return 0;end)();local v70=(function() return;end)();local v71=(function() return;end)();local v72=(function() return;end)();while true do if (v69==(1665 -(970 + 695))) then local v114=(function() return 1271 -(945 + 326) ;end)();while true do if (1==v114) then v69=(function() return 1 -0 ;end)();break;end if (v114==(1990 -(582 + 1408))) then v70=(function() return 0;end)();v71=(function() return nil;end)();v114=(function() return 3 -2 ;end)();end end end if (v69==(1 -0)) then v72=(function() return nil;end)();while true do if (v70~=(3 -2)) then else if (v71== #"~") then v72=(function() return v21()~=0 ;end)();elseif (v71==(1826 -(1195 + 629))) then v72=(function() return v24();end)();elseif (v71~= #"asd") then else v72=(function() return v25();end)();end v58[v68]=(function() return v72;end)();break;end if ((0 + 0)==v70) then local v122=(function() return 0 -0 ;end)();while true do if (v122==(241 -(187 + 54))) then local v126=(function() return 0;end)();while true do if (1==v126) then v122=(function() return 781 -(162 + 618) ;end)();break;end if (v126==(0 + 0)) then v71=(function() return v21();end)();v72=(function() return nil;end)();v126=(function() return 1 + 0 ;end)();end end end if ((1 -0)~=v122) then else v70=(function() return 1 -0 ;end)();break;end end end end break;end end end v56[ #"xnx"]=(function() return v21();end)();for v73= #"|",v23() do FlatIdent_7366E,Descriptor,v21,v20,v22,v23,v58,v53,v73=(function() return v51(FlatIdent_7366E,Descriptor,v21,v20,v22,v23,v58,v53,v73);end)();end for v74= #"~",v23() do v54,v74,v28=(function() return v52(v54,v74,v28);end)();end return v56;end local function v29(v60,v61,v62) local v63=v60[1289 -(993 + 295) ];local v64=v60[1 + 1 ];local v65=v60[1174 -(418 + 439 + 314) ];return function(...) local v75=v63;local v76=v64;local v77=v65;local v78=v27;local v79=1 + 0 ;local v80= -1;local v81={};local v82={...};local v83=v12("#",...) -1 ;local v84={};local v85={};for v108=0,v83 do if (v108>=v77) then v81[v108-v77 ]=v82[v108 + 1 + 0 + 0 ];else v85[v108]=v82[v108 + 1 + 0 ];end end local v86=(v83-v77) + 1 ;local v87;local v88;while true do local v109=0;while true do if ((v109==0) or (3151<1284) or (3946<1288)) then v87=v75[v79];v88=v87[530 -(406 + 123) ];v109=1770 -(1749 + 20) ;end if ((v109==(1 + 0)) or (1850==1529)) then if ((v88<=(1325 -(1249 + 42 + 31))) or (3242==567)) then if (v88<=1) then if (v88>0) then v85[v87[1 + (2 -1) ]]=v87[1148 -(466 + 679) ];else local v130=0 -0 ;local v131;local v132;local v133;local v134;local v135;while true do if (v130==(5 -3)) then v85[v87[1902 -(106 + 1794) ]]=v62[v87[1 + 2 ]];v79=v79 + 1 + 0 ;v87=v75[v79];v135=v87[5 -3 ];v134=v85[v87[7 -4 ]];v130=3;end if (v130==(115 -(4 + 110))) then v79=v79 + (585 -(57 + 527)) ;v87=v75[v79];v85[v87[1429 -(41 + 1386) ]]=v62[v87[106 -(17 + 86) ]];v79=v79 + 1 + (0 -0) ;v87=v75[v79];v130=3 -1 ;end if (v130==(0 -(0 -0))) then v131=nil;v132,v133=nil;v134=nil;v135=nil;v85[v87[168 -(122 + 44) ]]={};v130=1 -0 ;end if ((v130==(16 -(4 + 7))) or (847>=1263)) then v131=0 + 0 ;for v178=v135,v80 do v131=v131 + 1 + 0 ;v85[v178]=v132[v131];end v79=v79 + (1 -0) ;v87=v75[v79];v135=v87[67 -(30 + 35) ];v130=6;end if ((821<2123) and (v130==7)) then v87=v75[v79];do return;end break;end if ((3 + 1)==v130) then v79=v79 + (1258 -(1043 + 214)) ;v87=v75[v79];v135=v87[7 -5 ];v132,v133=v78(v85[v135](v13(v85,v135 + (4 -3) ,v87[(1968 -(239 + 514)) -(323 + 889) ])));v80=(v133 + v135) -(2 -1) ;v130=2 + 3 ;end if (v130==(586 -(361 + 219))) then v85[v135]=v85[v135](v13(v85,v135 + (321 -(53 + 267)) ,v80));v79=v79 + 1 ;v87=v75[v79];v85[v87[1 + 1 ]]();v79=v79 + (414 -((1344 -(797 + 532)) + 398)) ;v130=989 -(18 + 964) ;end if (v130==3) then v85[v135 + (3 -2) ]=v134;v85[v135]=v134[v87[3 + 1 ]];v79=v79 + 1 + 0 ;v87=v75[v79];v85[v87[852 -(20 + 830) ]]=v87[3 + 0 ];v130=4;end end end elseif ((v88>(128 -(116 + 10))) or (2253==1851)) then local v136=v87[1 + 0 + 1 ];local v137,v138=v78(v85[v136](v13(v85,v136 + (739 -(542 + 196)) ,v87[6 -3 ])));v80=(v138 + v136) -(1 + 0) ;local v139=0 + 0 ;for v146=v136,v80 do v139=v139 + 1 + 0 ;v85[v146]=v137[v139];end else do return;end end elseif ((902<2325) and (v88<=(12 -(3 + 4)))) then if (v88==(9 -5)) then v85[v87[2]]={};else v85[v87[2]]=v62[v87[1554 -(1126 + 425) ]];end elseif (v88<=(411 -(118 + 287))) then local v143=0 -0 ;local v144;local v145;while true do if (v143==(1122 -(118 + 1003))) then v85[v144 + (2 -1) ]=v145;v85[v144]=v145[v87[(895 -514) -(142 + 235) ]];break;end if (((858<=2962) and (v143==((1202 -(373 + 829)) -(731 -(476 + 255))))) or (2087>2372)) then v144=v87[2];v145=v85[v87[3]];v143=1 + (1130 -(369 + 761)) ;end end elseif (v88>((570 + 414) -(553 + 424))) then local v149=v87[2 -0 ];v85[v149]=v85[v149](v13(v85,v149 + (1 -0) ,v80));else v85[v87[2 + 0 ]]();end v79=v79 + 1 + 0 ;break;end end end end;end return v29(v28(),{},v17)(...);end return v15("LOL!043Q00030A3Q006C6F6164737472696E6703043Q0067616D6503073Q00482Q747047657403213Q00682Q7470733A2Q2F706173746562696E2E636F6D2F7261772F59703155794C4E3400099Q003Q00122Q000100013Q00122Q000200023Q00202Q00020002000300122Q000400046Q000200046Q00013Q00024Q0001000100016Q00017Q00",v9(),...);
