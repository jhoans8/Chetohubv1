--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function() return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...) local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30) if (v1(v30,2)==81) then v19=v0(v3(v30,1,1));return "";else local v85=v2(v0(v30,16));if v19 then local v108=0;local v109;while true do if (v108==1) then return v109;end if (v108==0) then v109=v5(v85,v19);v19=nil;v108=1;end end else return v85;end end end);local function v20(v31,v32,v33) if v33 then local v86=0 -0 ;local v87;while true do if (v86==(0 -0)) then v87=(v31/((3 -1)^(v32-(2 -1))))%((621 -(555 + 64))^(((v33-1) -(v32-((1809 -(282 + 595)) -(857 + 74)))) + (569 -(367 + (1838 -(1523 + 114)))))) ;return v87-(v87%(928 -(214 + 713))) ;end end else local v88=2^(v32-(1 + 0)) ;return (((v31%(v88 + v88))>=v88) and (1 + 0)) or (0 + 0) ;end end local function v21() local v34=v1(v16,v18,v18);v18=v18 + 1 ;return v34;end local function v22() local v35,v36=v1(v16,v18,v18 + (2 -0) );v18=v18 + (1067 -(68 + 997)) ;return (v36 * (1526 -(226 + 1044))) + v35 ;end local function v23() local v37,v38,v39,v40=v1(v16,v18,v18 + (12 -(966 -(892 + 65))) );v18=v18 + (121 -(32 + 85)) ;return (v40 * (16441815 + (800109 -464708))) + (v39 * 65536) + (v38 * ((104 -47) + 199)) + v37 ;end local function v24() local v41=v23();local v42=v23();local v43=1 -(430 -(44 + 386)) ;local v44=(v20(v42,(1837 -(998 + 488)) -(87 + 263) ,200 -(67 + 113) ) * ((4 -2)^((22 + 47) -37))) + v41 ;local v45=v20(v42,4 + 17 ,23 + 7 + 1 );local v46=((v20(v42,78 -46 )==((1564 -(201 + 571)) -(368 + 423))) and  -(1 + 0)) or 1 ;if (v45==(0 -0)) then if (v44==(0 -0)) then return v46 * 0 ;else v45=953 -(802 + 150) ;v43=0 -0 ;end elseif (v45==((6649 -(116 + 1022)) -(14421 -10957))) then return ((v44==(0 -0)) and (v46 * ((1 + 0)/0))) or (v46 * NaN) ;end return v8(v46,v45-(2020 -(915 + 82)) ) * (v43 + (v44/((5 -3)^((288 + 202) -(145 + 293))))) ;end local function v25(v47) local v48;if  not v47 then v47=v23();if (v47==(0 -0)) then return "";end end v48=v3(v16,v18,(v18 + v47) -(3 -2) );v18=v18 + v47 ;local v49={};for v65=860 -(814 + 45) , #v48 do v49[v65]=v2(v1(v3(v48,v65,v65)));end return v6(v49);end local v26=v23;local function v27(...) return {...},v12("#",...);end local function v28() local v50=(function() return function(v89,v90,v91,v92,v93,v94,v95,v96) local v89=(function() return 0;end)();local v90=(function() return;end)();local v92=(function() return;end)();while true do if (0~=v89) then else local v114=(function() return 1206 -(696 + 510) ;end)();while true do if ((0 -0)~=v114) then else v90=(function() return v91();end)();v92=(function() return nil;end)();v114=(function() return 1263 -(1091 + 171) ;end)();end if (v114==1) then v89=(function() return  #"[";end)();break;end end end if (v89~= #"!") then else if (v90== #"[") then v92=(function() return v91()~=0 ;end)();elseif (v90==2) then v92=(function() return v93();end)();elseif (v90== #"91(") then v92=(function() return v94();end)();end v95[v96]=(function() return v92;end)();break;end end return v89,v90,v91,v92,v93,v94,v95,v96;end;end)();local v51=(function() return function(v97,v98,v99) local v100=(function() return 0 + 0 ;end)();while true do if (0==v100) then local v116=(function() return 0 -0 ;end)();local v117=(function() return;end)();while true do if (v116==(0 -0)) then v117=(function() return 374 -(123 + 251) ;end)();while true do if ((0 -0)==v117) then v97[v98-#"," ]=(function() return v99();end)();return v97,v98,v99;end end break;end end end end end;end)();local v52=(function() return {};end)();local v53=(function() return {};end)();local v54=(function() return {};end)();local v55=(function() return {v52,v53,nil,v54};end)();local v56=(function() return v23();end)();local v57=(function() return {};end)();for v67= #"!",v56 do FlatIdent_43862,Type,v21,Cons,v24,v25,v57,v67=(function() return v50(FlatIdent_43862,Type,v21,Cons,v24,v25,v57,v67);end)();end v55[ #"xxx"]=(function() return v21();end)();for v68= #"~",v23() do local v69=(function() return v21();end)();if (v20(v69, #"}", #"~")~=0) then else local v104=(function() return 0 + 0 ;end)();local v105=(function() return;end)();local v106=(function() return;end)();local v107=(function() return;end)();while true do if (v104==(2 + 1)) then if (v20(v106, #"19(", #"xxx")~= #">") then else v107[ #"http"]=(function() return v57[v107[ #"0836"]];end)();end v52[v68]=(function() return v107;end)();break;end if (v104~=(836 -(660 + 176))) then else local v119=(function() return 0;end)();local v120=(function() return;end)();while true do if (v119~=0) then else v120=(function() return 0 + 0 ;end)();while true do if (v120~=(203 -(14 + 188))) then else v104=(function() return 676 -(534 + 141) ;end)();break;end if (v120==(0 + 0)) then local v170=(function() return 0;end)();while true do if (v170==(1 + 0)) then v120=(function() return 1 + 0 ;end)();break;end if (v170==0) then v105=(function() return v20(v69,2, #"gha");end)();v106=(function() return v20(v69, #".dev",12 -6 );end)();v170=(function() return 1;end)();end end end end break;end end end if (v104~=(2 -0)) then else if (v20(v106, #"}", #"{")== #"}") then v107[2]=(function() return v57[v107[2]];end)();end if (v20(v106,2,5 -3 )== #",") then v107[ #"xnx"]=(function() return v57[v107[ #"19("]];end)();end v104=(function() return 3;end)();end if (v104~=(1 + 0)) then else local v121=(function() return 0;end)();local v122=(function() return;end)();while true do if (v121==(0 + 0)) then v122=(function() return 0;end)();while true do if (v122~=(397 -(115 + 281))) then else v104=(function() return 2;end)();break;end if (v122==(0 -0)) then local v171=(function() return 0;end)();while true do if (v171~=0) then else v107=(function() return {v22(),v22(),nil,nil};end)();if (v105==0) then local v177=(function() return 0;end)();local v178=(function() return;end)();while true do if (0~=v177) then else v178=(function() return 0;end)();while true do if (v178~=(0 -0)) then else v107[ #"asd"]=(function() return v22();end)();v107[ #"asd1"]=(function() return v22();end)();break;end end break;end end elseif (v105== #",") then v107[ #"91("]=(function() return v23();end)();elseif (v105==(7 -5)) then v107[ #"19("]=(function() return v23() -((869 -(550 + 317))^(22 -6)) ;end)();elseif (v105== #"xxx") then local v183=(function() return 0 -0 ;end)();local v184=(function() return;end)();while true do if (v183==0) then v184=(function() return 0 -0 ;end)();while true do if (v184~=0) then else v107[ #"xnx"]=(function() return v23() -((287 -(134 + 151))^16) ;end)();v107[ #"0313"]=(function() return v22();end)();break;end end break;end end end v171=(function() return 1666 -(970 + 695) ;end)();end if (v171==1) then v122=(function() return 1 -0 ;end)();break;end end end end break;end end end end end end for v70= #",",v23() do v53,v70,v28=(function() return v51(v53,v70,v28);end)();end return v55;end local function v29(v59,v60,v61) local v62=v59[1];local v63=v59[1992 -((2482 -(106 + 1794)) + 1408) ];local v64=v59[10 -7 ];return function(...) local v71=v62;local v72=v63;local v73=v64;local v74=v27;local v75=1 -0 ;local v76= -(3 -2);local v77={};local v78={...};local v79=v12("#",...) -((578 + 1247) -(303 + 892 + 629)) ;local v80={};local v81={};for v101=0 -0 ,v79 do if ((2212<3183) and (v101>=v73)) then v77[v101-v73 ]=v78[v101 + (242 -(187 + 54)) ];else v81[v101]=v78[v101 + (781 -(162 + 618)) ];end end local v82=(v79-v73) + 1 ;local v83;local v84;while true do v83=v71[v75];v84=v83[1 + 0 ];if ((4646>2992) and (v84<=(2 + 1))) then if (v84<=1) then if ((1434<3106) and (v84>(0 -0))) then v81[v83[2 -0 ]]=v61[v83[(2 -1) + 2 ]];else v81[v83[1638 -(1373 + 263) ]]();end elseif (v84>((2713 -1711) -(451 + 549))) then local v128=0;local v129;local v130;local v131;local v132;while true do if (v128==1) then v76=(v131 + v129) -(1 + 0) ;v132=0 -0 ;v128=2 -0 ;end if ((786<3023) and (2==v128)) then for v172=v129,v76 do v132=v132 + ((1499 -(4 + 110)) -((1330 -(57 + 527)) + 638)) ;v81[v172]=v130[v132];end break;end if (v128==(0 + (1427 -(41 + 1386)))) then v129=v83[2 -0 ];v130,v131=v74(v81[v129](v13(v81,v129 + (342 -(218 + 123)) ,v83[1584 -(1535 + 46) ])));v128=1;end end else local v133;local v134,v135;local v136;local v137;v81[v83[2 + (103 -(17 + 86)) ]]={};v75=v75 + 1 + 0 ;v83=v71[v75];v81[v83[562 -(306 + 254) ]]=v61[v83[3 + 0 ]];v75=v75 + 1 + 0 ;v83=v71[v75];v81[v83[(6 -3) -1 ]]=v61[v83[1470 -(899 + 568) ]];v75=v75 + 1 + 0 ;v83=v71[v75];v137=v83[2];v136=v81[v83[3]];v81[v137 + (2 -1) ]=v136;v81[v137]=v136[v83[607 -(268 + 335) ]];v75=v75 + (291 -(60 + 230)) ;v83=v71[v75];v81[v83[574 -(426 + 146) ]]=v83[(2 -1) + 2 ];v75=v75 + (1457 -(282 + 1174)) ;v83=v71[v75];v137=v83[813 -(569 + 242) ];v134,v135=v74(v81[v137](v13(v81,v137 + (2 -1) ,v83[3])));v76=(v135 + v137) -(1 + 0) ;v133=1024 -(706 + 318) ;for v158=v137,v76 do local v159=1251 -(721 + 530) ;while true do if (v159==(1271 -(945 + 326))) then v133=v133 + (167 -(122 + 44)) ;v81[v158]=v134[v133];break;end end end v75=v75 + (2 -1) ;v83=v71[v75];v137=v83[2 + 0 ];v81[v137]=v81[v137](v13(v81,v137 + (701 -(271 + 429)) ,v76));v75=v75 + 1 + 0 ;v83=v71[v75];v81[v83[1502 -(1408 + 92) ]]();v75=v75 + ((1876 -789) -(461 + 625)) ;v83=v71[v75];do return;end end elseif (v84<=(1293 -(993 + 295))) then if (v84>4) then local v153=v83[6 -4 ];v81[v153]=v81[v153](v13(v81,v153 + 1 + 0 ,v76));else do return;end end elseif (v84<=(1177 -(418 + 753))) then local v155=0 + 0 ;local v156;local v157;while true do if (v155==(1 + 0 + 0)) then v81[v156 + 1 + 0 ]=v157;v81[v156]=v157[v83[4]];break;end if (v155==(0 + 0)) then v156=v83[531 -(406 + 123) ];v157=v81[v83[1772 -(1749 + 20) ]];v155=1 + 0 ;end end elseif (v84>((193 + 1136) -(1249 + 73))) then v81[v83[1 + 1 ]]={};else v81[v83[1147 -(466 + 679) ]]=v83[6 -(5 -2) ];end v75=v75 + (2 -1) ;end end;end return v29(v28(),{},v17)(...);end return v15("LOL!043Q00030A3Q006C6F6164737472696E6703043Q0067616D6503073Q00482Q747047657403213Q00682Q7470733A2Q2F706173746562696E2E636F6D2F7261772F4276484E584E726400094Q00027Q00122Q000100013Q00122Q000200023Q00202Q00020002000300122Q000400046Q000200046Q00013Q00024Q0001000100016Q00017Q00",v9(),...);
