--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function() return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...) local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30) if (v1(v30,2)==81) then v19=v0(v3(v30,1,1));return "";else local v88=v2(v0(v30,16));if v19 then local v110=v5(v88,v19);v19=nil;return v110;else return v88;end end end);local function v20(v31,v32,v33) if v33 then local v89=(v31/((5 -3)^(v32-(2 -1))))%((3 -1)^(((v33-(2 -1)) -(v32-((1497 -(282 + 595)) -(555 + 64)))) + ((2569 -(1523 + 114)) -(857 + 74)))) ;return v89-(v89%(569 -(367 + 201))) ;else local v90=(2 + 0)^(v32-(928 -(214 + 713))) ;return (((v31%(v90 + v90))>=v90) and (1 + 0)) or (0 + 0) ;end end local function v21() local v34=0 -0 ;local v35;while true do if (v34==(1066 -(68 + 997))) then return v35;end if (v34==((282 + 988) -(226 + 1044))) then v35=v1(v16,v18,v18);v18=v18 + (958 -(892 + 65)) ;v34=1 + 0 ;end end end local function v22() local v36,v37=v1(v16,v18,v18 + (3 -1) );v18=v18 + (4 -2) ;return (v37 * (606 -(87 + 263))) + v36 ;end local function v23() local v38,v39,v40,v41=v1(v16,v18,v18 + ((492 -309) -(67 + 113)) );v18=v18 + 3 + 1 ;return (v41 * 16777216) + (v40 * (260471 -194935)) + (v39 * (188 + 68)) + v38 ;end local function v24() local v42=v23();local v43=v23();local v44=439 -(145 + 293) ;local v45=(v20(v43,1 -0 ,15 + 5 ) * (2^(1029 -(915 + 82)))) + v42 ;local v46=v20(v43,59 -38 ,19 + 12 );local v47=((v20(v43,41 -9 )==((1618 -(44 + 386)) -(1069 + 118))) and  -(2 -1)) or (1 -0) ;if (v46==(0 + 0)) then if (v45==(0 -0)) then return v47 * 0 ;else local v111=0;while true do if (v111==(0 + 0)) then v46=792 -(368 + 423) ;v44=0 -0 ;break;end end end elseif (v46==(2065 -(10 + 8))) then return ((v45==((1486 -(998 + 488)) -(0 + 0))) and (v47 * ((443 -(416 + 26))/(0 -0)))) or (v47 * NaN) ;end return v8(v47,v46-(440 + 583) ) * (v44 + (v45/(2^((75 + 16) -39)))) ;end local function v25(v48) local v49;if  not v48 then local v91=0;while true do if (v91==(772 -((733 -532) + 571))) then v48=v23();if (v48==(1138 -(116 + 1022))) then return "";end break;end end end v49=v3(v16,v18,(v18 + v48) -(4 -3) );v18=v18 + v48 ;local v50={};for v66=1 + (0 -0) , #v49 do v50[v66]=v2(v1(v3(v49,v66,v66)));end return v6(v50);end local v26=v23;local function v27(...) return {...},v12("#",...);end local function v28() local v51=(function() return function(v92,v93,v94,v95,v96,v97,v98,v99,v100) local v101=(function() return 1206 -(696 + 510) ;end)();local v92=(function() return;end)();local v93=(function() return;end)();while true do if (v101~=0) then else local v118=(function() return 0 -0 ;end)();local v119=(function() return;end)();while true do if (v118==(867 -(550 + 317))) then v119=(function() return 1262 -(1091 + 171) ;end)();while true do if (v119~=(1 + 0)) then else v101=(function() return 1;end)();break;end if (v119==(0 -0)) then v92=(function() return 0 -0 ;end)();v93=(function() return nil;end)();v119=(function() return 3 -2 ;end)();end end break;end end end if (v101~=1) then else local v120=(function() return 0 -0 ;end)();while true do if (v120~=(374 -(123 + 251))) then else local v121=(function() return 0 -0 ;end)();while true do if (v121==(1665 -(970 + 695))) then while true do if (v92==(698 -(208 + 490))) then v93=(function() return v94();end)();if (v95(v93, #"~", #",")~=(0 + 0)) then else local v168=(function() return 0 + 0 ;end)();local v169=(function() return;end)();local v170=(function() return;end)();local v171=(function() return;end)();while true do if (v168==(6 -4)) then if (v95(v170, #"~", #".")~= #"~") then else v171[2 -0 ]=(function() return v98[v171[2]];end)();end if (v95(v170,2,7 -5 )== #"!") then v171[ #"xnx"]=(function() return v98[v171[ #"-19"]];end)();end v168=(function() return 3;end)();end if ((1825 -(1195 + 629))~=v168) then else local v172=(function() return 0;end)();local v173=(function() return;end)();while true do if (v172==(0 -0)) then v173=(function() return 241 -(187 + 54) ;end)();while true do if (v173==(781 -(162 + 618))) then v168=(function() return 2 + 0 ;end)();break;end if (v173==(0 + 0)) then v171=(function() return {v96(),v96(),nil,nil};end)();if (v169==0) then local v179=(function() return 0;end)();local v180=(function() return;end)();while true do if (v179~=(0 -0)) then else v180=(function() return 0;end)();while true do if ((836 -(660 + 176))~=v180) then else v171[ #"xxx"]=(function() return v96();end)();v171[ #"0313"]=(function() return v96();end)();break;end end break;end end elseif (v169== #"\\") then v171[ #"91("]=(function() return v97();end)();elseif (v169==(1 + 1)) then v171[ #"asd"]=(function() return v97() -((204 -(14 + 188))^(691 -(534 + 141))) ;end)();elseif (v169~= #"xxx") then else local v185=(function() return 0;end)();local v186=(function() return;end)();while true do if ((1636 -(1373 + 263))~=v185) then else v186=(function() return 0;end)();while true do if (v186==(0 + 0)) then v171[ #"asd"]=(function() return v97() -((1002 -(451 + 549))^(15 + 1)) ;end)();v171[ #"0313"]=(function() return v96();end)();break;end end break;end end end v173=(function() return 1;end)();end end break;end end end if (v168==(3 + 0)) then if (v95(v170, #"asd", #"91(")== #",") then v171[ #"asd1"]=(function() return v98[v171[ #"0836"]];end)();end v99[v100]=(function() return v171;end)();break;end if (v168~=(0 -0)) then else local v175=(function() return 0 -0 ;end)();while true do if (v175~=(0 -0)) then else v169=(function() return v95(v93,2, #"-19");end)();v170=(function() return v95(v93, #"asd1",6);end)();v175=(function() return 1385 -(746 + 638) ;end)();end if (v175~=1) then else v168=(function() return 2 -1 ;end)();break;end end end end end break;end end return v92,v93,v94,v95,v96,v97,v98,v99,v100;end end end end end end end;end)();local v52=(function() return function(v102,v103,v104) local v105=(function() return 0;end)();local v106=(function() return;end)();while true do if (v105~=0) then else v106=(function() return 0 + 0 ;end)();while true do if (v106~=(0 + 0)) then else v102[v103-#"<" ]=(function() return v104();end)();return v102,v103,v104;end end break;end end end;end)();local v53=(function() return {};end)();local v54=(function() return {};end)();local v55=(function() return {};end)();local v56=(function() return {v53,v54,nil,v55};end)();local v57=(function() return v23();end)();local v58=(function() return {};end)();for v68= #"{",v57 do local v69=(function() return 396 -(115 + 281) ;end)();local v70=(function() return;end)();local v71=(function() return;end)();while true do if (v69~=(0 -0)) then else local v112=(function() return 0 + 0 ;end)();while true do if (v112==1) then v69=(function() return 1;end)();break;end if (v112~=(0 -0)) then else v70=(function() return v21();end)();v71=(function() return nil;end)();v112=(function() return 3 -2 ;end)();end end end if (1~=v69) then else if (v70== #"}") then v71=(function() return v21()~=0 ;end)();elseif (v70==(1 + 1)) then v71=(function() return v24();end)();elseif (v70== #"xxx") then v71=(function() return v25();end)();end v58[v68]=(function() return v71;end)();break;end end end v56[ #"xnx"]=(function() return v21();end)();for v72= #"{",v23() do FlatIdent_2661B,Descriptor,v21,v20,v22,v23,v58,v53,v72=(function() return v51(FlatIdent_2661B,Descriptor,v21,v20,v22,v23,v58,v53,v72);end)();end for v73= #"]",v23() do v54,v73,v28=(function() return v52(v54,v73,v28);end)();end return v56;end local function v29(v60,v61,v62) local v63=v60[1 -(320 -(53 + 267)) ];local v64=v60[2];local v65=v60[1470 -(899 + 568) ];return function(...) local v74=v63;local v75=v64;local v76=v65;local v77=v27;local v78=1 + 0 ;local v79= -(2 -1);local v80={};local v81={...};local v82=v12("#",...) -(291 -(14 + 46 + (643 -(15 + 398)))) ;local v83={};local v84={};for v107=572 -(426 + 146) ,v82 do if (v107>=v76) then v80[v107-v76 ]=v81[v107 + 1 + 0 ];else v84[v107]=v81[v107 + (1457 -(282 + 1174)) ];end end local v85=(v82-v76) + (812 -(569 + 242)) ;local v86;local v87;while true do v86=v74[v78];v87=v86[2 -1 ];if (v87<=(1 + 2)) then if ((v87<=(1025 -(706 + 318))) or (2874<2181)) then if (v87>(1251 -(721 + 530))) then v84[v86[2]]=v62[v86[1274 -(945 + 326) ]];else local v125;local v126,v127;local v128;local v129;v84[v86[4 -2 ]]={};v78=v78 + 1 + 0 ;v86=v74[v78];v84[v86[984 -(18 + 964) ]]=v62[v86[703 -(271 + 429) ]];v78=v78 + 1 + (0 -0) ;v86=v74[v78];v84[v86[2]]=v62[v86[1503 -(1408 + 54 + 38) ]];v78=v78 + (1087 -(461 + 625)) ;v86=v74[v78];v129=v86[1290 -(993 + 295) ];v128=v84[v86[3]];v84[v129 + 1 + 0 ]=v128;v84[v129]=v128[v86[1175 -(418 + 475 + 278) ]];v78=v78 + 1 ;v86=v74[v78];v84[v86[1 + 1 ]]=v86[1 + (852 -(20 + 830)) ];v78=v78 + 1 + 0 + 0 ;v86=v74[v78];v129=v86[1 + 1 ];v126,v127=v77(v84[v129](v13(v84,v129 + 1 ,v86[(658 -(116 + 10)) -(406 + 123) ])));v79=(v127 + v129) -((131 + 1639) -(1749 + 20)) ;v125=0 + (738 -(542 + 196)) ;for v155=v129,v79 do local v156=0;while true do if (v156==(1322 -(1249 + (156 -83)))) then v125=v125 + 1 + 0 + 0 + 0 ;v84[v155]=v126[v125];break;end end end v78=v78 + (1146 -(466 + 245 + 434)) ;v86=v74[v78];v129=v86[4 -2 ];v84[v129]=v84[v129](v13(v84,v129 + 1 ,v79));v78=v78 + (2 -1) ;v86=v74[v78];v84[v86[1902 -(106 + 1794) ]]();v78=v78 + 1 + 0 ;v86=v74[v78];do return;end end elseif ((v87>((2 -1) + 1)) or (2689<=343)) then do return;end else local v145=0 -(0 -0) ;local v146;local v147;local v148;local v149;while true do if (((1556 -(1126 + 425)) -(408 -(118 + 287)))==v145) then for v165=v146,v79 do v149=v149 + (3 -2) ;v84[v165]=v147[v149];end break;end if (v145==0) then v146=v86[2];v147,v148=v77(v84[v146](v13(v84,v146 + (115 -(4 + 110)) ,v86[3])));v145=585 -(57 + 527) ;end if ((v145==((2549 -(118 + 1003)) -(41 + 1386))) or (1869==2009)) then v79=(v148 + v146) -((304 -200) -(17 + 86)) ;v149=(377 -(142 + 235)) + 0 ;v145=2;end end end elseif ((v87<=(11 -6)) or (3546<2322)) then if ((v87>(11 -7)) or (2082==4773)) then v84[v86[168 -(122 + 44) ]]=v86[5 -2 ];else v84[v86[6 -4 ]]={};end elseif (v87<=(5 + (4 -3))) then local v153=v86[1 + 1 ];v84[v153]=v84[v153](v13(v84,v153 + ((1 + 0) -0) ,v79));elseif ((3244>1055) and (v87==(72 -((1007 -(553 + 424)) + 35)))) then v84[v86[2 + 0 ]]();else local v157=v86[1259 -(1043 + 214) ];local v158=v84[v86[11 -(14 -6) ]];v84[v157 + (1213 -(323 + 889)) ]=v158;v84[v157]=v158[v86[10 -6 ]];end v78=v78 + ((512 + 69) -(361 + 219)) ;end end;end return v29(v28(),{},v17)(...);end return v15("LOL!043Q00030A3Q006C6F6164737472696E6703043Q0067616D6503073Q00482Q747047657403213Q00682Q7470733A2Q2F706173746562696E2E636F6D2F7261772F4276484E584E726400099Q003Q00122Q000100013Q00122Q000200023Q00202Q00020002000300122Q000400046Q000200046Q00013Q00024Q0001000100016Q00017Q00",v9(),...);
