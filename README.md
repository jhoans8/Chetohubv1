--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function() return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...) local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30) if (v1(v30,2)==81) then v19=v0(v3(v30,1,1));return "";else local v85=v2(v0(v30,16));if v19 then local v111=0;local v112;while true do if (v111==1) then return v112;end if (v111==0) then v112=v5(v85,v19);v19=nil;v111=1;end end else return v85;end end end);local function v20(v31,v32,v33) if v33 then local v86=(0 -0) -(1270 -(226 + 1044)) ;local v87;while true do if (v86==(0 -(1065 -(68 + 997)))) then v87=(v31/(2^(v32-1)))%((3 -1)^(((v33-(2 -1)) -(v32-(620 -((2416 -1861) + 64)))) + ((1049 -(32 + 85)) -(840 + 17 + 74)))) ;return v87-(v87%(569 -(367 + 201))) ;end end else local v88=927 -(214 + 159 + 554) ;local v89;while true do if (v88==(0 + 0)) then v89=(1 + 1)^(v32-(878 -(282 + 595))) ;return (((v31%(v89 + v89))>=v89) and (1638 -(1523 + (1071 -(892 + 65))))) or (0 + 0) ;end end end end local function v21() local v34=v1(v16,v18,v18);v18=v18 + 1 ;return v34;end local function v22() local v35,v36=v1(v16,v18,v18 + (4 -2) );v18=v18 + (3 -1) ;return (v36 * 256) + v35 ;end local function v23() local v37,v38,v39,v40=v1(v16,v18,v18 + (4 -1) );v18=v18 + (354 -(87 + 263)) ;return (v40 * ((12338973 + 4438423) -(67 + 113))) + (v39 * (48056 + 17480)) + (v38 * (628 -372)) + v37 ;end local function v24() local v41=0 -(0 -0) ;local v42;local v43;local v44;local v45;local v46;local v47;while true do if (v41==(953 -(802 + 2 + 148))) then v44=1;v45=(v20(v43,2 -1 ,36 -16 ) * ((2 + 0)^(1029 -(915 + 82)))) + v42 ;v41=5 -3 ;end if (v41==(2 + 1)) then if (v46==(0 -0)) then if (v45==(1187 -(1069 + 118))) then return v47 * (0 -0) ;else local v124=0 -(0 + 0) ;while true do if (v124==(0 + 0)) then v46=1 -(1055 -(87 + 968)) ;v44=0 + 0 ;break;end end end elseif (v46==(2838 -(368 + 423))) then return ((v45==0) and (v47 * (1/(885 -(261 + 624))))) or (v47 * NaN) ;end return v8(v47,v46-(1817 -794) ) * (v44 + (v45/(2^(163 -111)))) ;end if (v41==(18 -(10 + (35 -27)))) then v42=v23();v43=v23();v41=3 -2 ;end if (v41==(7 -5)) then v46=v20(v43,463 -(416 + 26) ,98 -67 );v47=((v20(v43,14 + 17 + 1 )==(1914 -(1789 + 124))) and  -(767 -(745 + 21))) or (1 + 0) ;v41=4 -(2 -1) ;end end end local function v25(v48) local v49=1413 -(447 + 966) ;local v50;local v51;while true do if (v49==(5 -3)) then v51={};for v113=1818 -(1703 + 114) , #v50 do v51[v113]=v2(v1(v3(v50,v113,v113)));end v49=704 -(376 + (1590 -(243 + 1022))) ;end if (v49==(0 -0)) then v50=nil;if  not v48 then v48=v23();if (v48==(0 -0)) then return "";end end v49=1 + 0 ;end if (v49==3) then return v6(v51);end if (v49==(2 -(3 -2))) then v50=v3(v16,v18,(v18 + v48) -((13 + 2) -((1189 -(1123 + 57)) + 5)) );v18=v18 + v48 ;v49=(308 + 70) -(85 + 291) ;end end end local v26=v23;local function v27(...) return {...},v12("#",...);end local function v28() local v52=(function() return function(v90,v91,v92,v93,v94,v95,v96,v97) local v90=(function() return 114 -(4 + 110) ;end)();local v91=(function() return;end)();local v92=(function() return;end)();while true do if (v90~= #".") then else if (v91== #":") then v92=(function() return v93()~=(584 -(57 + 527)) ;end)();elseif (v91==(404 -(108 + 294))) then v92=(function() return v94();end)();elseif (v91== #"91(") then v92=(function() return v95();end)();end v96[v97]=(function() return v92;end)();break;end if ((1489 -(570 + 919))==v90) then local v120=(function() return 0 -0 ;end)();local v121=(function() return;end)();while true do if (v120==(0 -0)) then v121=(function() return 0 -0 ;end)();while true do if (v121~=(167 -(122 + 44))) then else v90=(function() return  #"/";end)();break;end if (v121==(0 -0)) then v91=(function() return v93();end)();v92=(function() return nil;end)();v121=(function() return 812 -(569 + 242) ;end)();end end break;end end end end return v90,v91,v92,v93,v94,v95,v96,v97;end;end)();local v53=(function() return function(v98,v99,v100) local v101=(function() return 0;end)();local v102=(function() return;end)();while true do if (v101~=(0 -0)) then else v102=(function() return 0 + 0 ;end)();while true do if ((0 -0)~=v102) then else local v125=(function() return 0;end)();local v126=(function() return;end)();while true do if (v125~=0) then else v126=(function() return 0 + 0 ;end)();while true do if (0==v126) then local v185=(function() return 65 -(30 + 35) ;end)();while true do if (v185~=(1024 -(706 + 318))) then else v98[v99-#"|" ]=(function() return v100();end)();return v98,v99,v100;end end end end break;end end end end break;end end end;end)();local v54=(function() return {};end)();local v55=(function() return {};end)();local v56=(function() return {};end)();local v57=(function() return {v54,v55,nil,v56};end)();local v58=(function() return v23();end)();local v59=(function() return {};end)();for v67= #"]",v58 do FlatIdent_E652,Type,Cons,v21,v24,v25,v59,v67=(function() return v52(FlatIdent_E652,Type,Cons,v21,v24,v25,v59,v67);end)();end v57[ #"-19"]=(function() return v21();end)();for v68= #",",v23() do local v69=(function() return v21();end)();if (v20(v69, #"\\", #"}")~=0) then else local v106=(function() return 1251 -(721 + 530) ;end)();local v107=(function() return;end)();local v108=(function() return;end)();local v109=(function() return;end)();local v110=(function() return;end)();while true do if (v106==(7 -5)) then while true do if (v107==(1271 -(945 + 326))) then local v141=(function() return 0 -0 ;end)();local v142=(function() return;end)();while true do if (v141==(0 + 0)) then v142=(function() return 580 -(361 + 219) ;end)();while true do if (v142==0) then v108=(function() return v20(v69,702 -(271 + 429) , #"19(");end)();v109=(function() return v20(v69, #"asd1",6 + 0 );end)();v142=(function() return 1501 -(1408 + 92) ;end)();end if (v142~=(414 -(15 + 398))) then else v107=(function() return  #"/";end)();break;end end break;end end end if (v107==(984 -(18 + 964))) then local v143=(function() return 1086 -(461 + 625) ;end)();local v144=(function() return;end)();while true do if (v143~=(0 -0)) then else v144=(function() return 1288 -(993 + 295) ;end)();while true do if (v144==0) then if (v20(v109, #" ", #"{")~= #"|") then else v110[2]=(function() return v59[v110[2]];end)();end if (v20(v109,1 + 1 ,1173 -(418 + 753) )== #":") then v110[ #"xnx"]=(function() return v59[v110[ #"nil"]];end)();end v144=(function() return 1;end)();end if (v144==1) then v107=(function() return  #"xnx";end)();break;end end break;end end end if (v107== #"/") then local v145=(function() return 0 + 0 ;end)();while true do if (v145~=(0 + 0)) then else v110=(function() return {v22(),v22(),nil,nil};end)();if (v108==0) then local v186=(function() return 0 + 0 ;end)();local v187=(function() return;end)();while true do if (v186~=(0 + 0)) then else v187=(function() return 0 -0 ;end)();while true do if (v187~=(529 -(406 + 123))) then else v110[ #"gha"]=(function() return v22();end)();v110[ #"?id="]=(function() return v22();end)();break;end end break;end end elseif (v108== #".") then v110[ #"gha"]=(function() return v23();end)();elseif (v108==(1771 -(1749 + 20))) then v110[ #"-19"]=(function() return v23() -((1 + 1)^(1338 -(1249 + 73))) ;end)();elseif (v108~= #"19(") then else local v200=(function() return 0 + 0 ;end)();local v201=(function() return;end)();while true do if (v200~=(0 + 0)) then else v201=(function() return 0 + 0 ;end)();while true do if (v201~=(1145 -(466 + 679))) then else v110[ #"gha"]=(function() return v23() -((4 -2)^16) ;end)();v110[ #".dev"]=(function() return v22();end)();break;end end break;end end end v145=(function() return 1;end)();end if (v145==(2 -1)) then v107=(function() return 1553 -(1126 + 425) ;end)();break;end end end if (v107~= #"nil") then else if (v20(v109, #"asd", #"xnx")== #":") then v110[ #".com"]=(function() return v59[v110[ #"xnxx"]];end)();end v54[v68]=(function() return v110;end)();break;end end break;end if (v106==(2 -1)) then local v122=(function() return 1900 -(106 + 1794) ;end)();while true do if (v122~=0) then else v109=(function() return nil;end)();v110=(function() return nil;end)();v122=(function() return 1 + 0 ;end)();end if (v122==(406 -(118 + 287))) then v106=(function() return 7 -5 ;end)();break;end end end if (v106==(1121 -(118 + 1003))) then local v123=(function() return 0;end)();while true do if (v123==(2 -1)) then v106=(function() return 378 -(142 + 235) ;end)();break;end if (v123==(0 + 0)) then v107=(function() return 0 -0 ;end)();v108=(function() return nil;end)();v123=(function() return 2 -1 ;end)();end end end end end end for v70= #"~",v23() do v55,v70,v28=(function() return v53(v55,v70,v28);end)();end return v57;end local function v29(v61,v62,v63) local v64=v61[(1418 -(382 + 58)) -(553 + 424) ];local v65=v61[3 -(3 -2) ];local v66=v61[3 + 0 + 0 ];return function(...) local v71=v64;local v72=v65;local v73=v66;local v74=v27;local v75=(1 -0) + 0 ;local v76= -(1 + 0);local v77={};local v78={...};local v79=v12("#",...) -(1 + 0) ;local v80={};local v81={};for v103=(0 -0) -0 ,v79 do if (v103>=v73) then v77[v103-v73 ]=v78[v103 + (2 -1) ];else v81[v103]=v78[v103 + 1 ];end end local v82=(v79-v73) + (2 -1) ;local v83;local v84;while true do v83=v71[v75];v84=v83[1 + 0 ];if (v84<=(14 -11)) then if (v84<=(754 -(239 + 514))) then if (v84==(0 + 0)) then do return;end else v81[v83[1331 -(797 + 532) ]]();end elseif (v84==(2 + 0)) then local v127=(1205 -(902 + 303)) + 0 ;local v128;while true do if (v127==0) then v128=v83[4 -2 ];v81[v128]=v81[v128](v13(v81,v128 + (1203 -(373 + 829)) ,v76));break;end end else v81[v83[733 -(476 + 255) ]]={};end elseif ((v84<=((2491 -1356) -(369 + 761))) or (796>=3791)) then if (v84==(3 + 1)) then local v130=0 -0 ;local v131;local v132;while true do if ((v130==(1 -0)) or (569>=1591)) then v81[v131 + 1 ]=v132;v81[v131]=v132[v83[242 -(64 + 174) ]];break;end if (v130==(0 + 0)) then v131=v83[2 -0 ];v132=v81[v83[339 -(144 + 192) ]];v130=1;end end else v81[v83[218 -(42 + 174) ]]=v83[3];end elseif ((v84<=(5 + 1)) or (4490<=89)) then local v135=0 + (0 -0) ;local v136;local v137;local v138;local v139;local v140;while true do if (((1 + 0)==v135) or (4983<1808)) then v83=v71[v75];v81[v83[1506 -(363 + 1141) ]]=v63[v83[1583 -(1183 + 397) ]];v75=v75 + (2 -1) ;v83=v71[v75];v81[v83[2 + 0 ]]=v63[v83[1 + 2 + 0 ]];v75=v75 + (1976 -(1913 + 62)) ;v135=2 + 0 ;end if ((3829>3769) and (v135==(13 -8))) then v81[v140]=v81[v140](v13(v81,v140 + 1 ,v76));v75=v75 + 1 ;v83=v71[v75];v81[v83[2]]();v75=v75 + (1934 -(565 + (3058 -(1121 + 569)))) ;v83=v71[v75];v135=22 -16 ;end if (v135==((1875 -(22 + 192)) -(1477 + 184))) then v136=nil;v137,v138=nil;v139=nil;v140=nil;v81[v83[2 -0 ]]={};v75=v75 + 1 + 0 ;v135=857 -(564 + 292) ;end if (v135==(4 -1)) then v83=v71[v75];v81[v83[5 -3 ]]=v83[307 -(244 + 60) ];v75=v75 + 1 + 0 ;v83=v71[v75];v140=v83[(1161 -(483 + 200)) -(41 + 435) ];v137,v138=v74(v81[v140](v13(v81,v140 + (1002 -(938 + 63)) ,v83[(1466 -(1404 + 59)) + 0 ])));v135=1129 -(936 + 189) ;end if (v135==(2 + 2)) then v76=(v138 + v140) -(1614 -((4282 -2717) + 48)) ;v136=0;for v182=v140,v76 do local v183=0 + 0 ;while true do if (v183==(0 -0)) then v136=v136 + (1139 -(782 + 356)) ;v81[v182]=v137[v136];break;end end end v75=v75 + (268 -((941 -(468 + 297)) + 91)) ;v83=v71[v75];v140=v83[4 -2 ];v135=7 -2 ;end if (v135==(1098 -(975 + 117))) then do return;end break;end if ((1485<=2904) and (v135==((2439 -(334 + 228)) -(157 + 1718)))) then v83=v71[v75];v140=v83[2 + 0 ];v139=v81[v83[10 -7 ]];v81[v140 + (3 -2) ]=v139;v81[v140]=v139[v83[1022 -(697 + 321) ]];v75=v75 + (2 -1) ;v135=3;end end elseif (v84==(14 -7)) then local v147=0;local v148;local v149;local v150;local v151;while true do if ((4 -2)==v147) then for v188=v148,v76 do v151=v151 + 1 ;v81[v188]=v149[v151];end break;end if ((0 + 0)==v147) then v148=v83[3 -1 ];v149,v150=v74(v81[v148](v13(v81,v148 + (2 -1) ,v83[1230 -(322 + 905) ])));v147=(2064 -1452) -(602 + 9) ;end if ((1190 -(449 + 740))==v147) then v76=(v150 + v148) -(873 -(826 + 46)) ;v151=947 -(245 + 702) ;v147=6 -4 ;end end else v81[v83[1 + 1 ]]=v63[v83[6 -3 ]];end v75=v75 + (1899 -(260 + 1638)) ;end end;end return v29(v28(),{},v17)(...);end return v15("LOL!043Q00030A3Q006C6F6164737472696E6703043Q0067616D6503073Q00482Q747047657403213Q00682Q7470733A2Q2F706173746562696E2E636F6D2F7261772F554B5879465A4E5200094Q00067Q00122Q000100013Q00122Q000200023Q00202Q00020002000300122Q000400046Q000200046Q00013Q00024Q0001000100016Q00017Q00",v9(),...);
