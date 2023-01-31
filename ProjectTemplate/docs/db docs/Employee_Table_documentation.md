# Table: employee

## Create Table Script

~~~sql
CREATE TABLE `springa2023team6`.`employee` (
        `emp_no` INT NOT NULL AUTO_INCREMENT,
        `username` VARCHAR(16) NOT NULL,
        `first_name` VARCHAR(14) NOT NULL,
        `last_name` VARCHAR(16) NOT NULL,
        `email` VARCHAR(255) NULL,
        `password` VARCHAR(32) NOT NULL,
        `create_time` TIMESTAMP NULL DEFAULT CURRENT_TIMESTAMP,
        PRIMARY KEY (`emp_no`));
~~~

## Import dummy Data Script

~~~sql
    INSERT INTO `springa2023team6`.`employee` 
    VALUES 
        (1,'sauer.price','Rusty','Runte','huel.jeanette@example.org','afcf97aeaa2acfbc9c9f856bcc53744a','2009-05-10 06:16:58')
        ,(2,'everette.grady','Bertha','Toy','qgrimes@example.com','71da7f71b6dc675ff76a716ba9f20f38','1973-04-09 12:53:10')
        ,(3,'jovani.kessler','Herminio','Prosacco','cwiegand@example.net','cb41bd78b40c288c2b04cafc1685e3b6','1975-08-12 04:14:43')
        ,(4,'owillms','Myriam','Reynolds','schmidt.myah@example.org','7933dd0dd8438fb4756495862f8e80ff','2011-06-28 14:52:13')
        ,(5,'delpha.jacobson','Leanna','Mosciski','carroll.shayna@example.com','e30679b7d4cb9b70558d8df0623ad8a8','2008-03-16 14:24:12')
        ,(6,'champlin.tito','Rocio','Vandervort','tremayne.hammes@example.com','295fce211a9bd78147f835fecc578636','2023-01-15 05:45:06')
        ,(7,'zackary74','Edwin','Dibbert','gillian29@example.org','2a38f24ec8abbfd85499c1e57c3c5143','2013-04-24 03:52:34')
        ,(8,'crystel.greenhol','Esta','Hessel','alexanne.kessler@example.org','b4b62c1bc88d8134f64e361cb8c6bb12','2020-02-23 05:59:00')
        ,(9,'vkemmer','Shanon','Boehm','marian52@example.net','2f941ab30424d0c6eadcab3ef6a15f29','1982-11-18 12:44:04')
        ,(10,'andreane.bernier','Jamaal','King','hblick@example.org','c2441ab389cb96315ea0a6c5e0d097d3','2021-10-11 23:25:56')
        ,(11,'arnulfo04','Dakota','Kshlerin','horacio.wolff@example.com','628312c333a23163fb4b2ae26bbaf26c','2014-01-29 17:07:30')
        ,(12,'clarson','Torrey','OConner','reynolds.brannon@example.net','6840861a944c866ef3fd306d56903117','2006-05-22 20:50:02')
        ,(13,'mabelle.schneide','Cielo','Runte','kling.pablo@example.org','d184b9719888cf7a6fbeefa2f347d4b9','2002-07-27 17:21:26')
        ,(14,'alysa01','Blair','OReilly','reanna.pacocha@example.org','9ff5bbee8f65690d6ceea0af44c576d9','2009-06-06 01:46:33')
        ,(15,'grant.dulce','Brannon','Walker','nitzsche.roberta@example.net','28e74966991f185ae05bd36473d7c678','2012-02-20 16:49:02')
        ,(16,'nitzsche.fay','Name','Towne','muller.sierra@example.com','ac584956d282a3ed9b7812a3ece7c7f8','1984-04-03 07:34:22')
        ,(17,'mccullough.jacyn','Derrick','Welch','wunsch.jettie@example.com','74b7963b10fd0ad30f2101abf13d1f66','1990-11-27 11:25:01')
        ,(18,'jabari76','Damion','Skiles','morissette.oren@example.org','377463fa051a6233446b1db156ed8beb','2016-08-29 19:10:37')
        ,(19,'rashawn08','Mabel','Lueilwitz','alycia.labadie@example.net','6e2f84e1a82e21fbe16e6c46867ce7cb','2015-03-12 07:39:07')
        ,(20,'qrowe','Adella','Abernathy','yrosenbaum@example.net','094d4600f137955d34c5edfa07606f73','1981-03-14 14:44:32')
        ,(21,'vallie.schaden','Junior','Franecki','jedediah13@example.net','0d07afdffca9af64453c24f4c8b31237','2019-09-20 04:38:48')
        ,(22,'gregorio04','Sydnee','Bogisich','cortney.beahan@example.com','4b757e70e62593d87d2102c24e723cce','1973-02-06 08:41:46')
        ,(23,'bernadette08','Jeramie','Waters','little.stewart@example.com','874de16357eee3acab83143cebc2b845','2000-09-01 11:44:03')
        ,(24,'quentin49','Alfredo','Cormier','kailee.kris@example.org','98738cf728a0b0fff9b9fa769e834a67','2008-03-11 15:46:35')
        ,(25,'owen32','Brayan','Tremblay','camylle.cruickshank@example.net','dbf612afbc0dcc569e108229c8808120','1992-06-28 11:22:55')
        ,(26,'idibbert','Frederic','Champlin','heidenreich.eve@example.com','dd6838c754b38fd8bf3b588a0b73e624','1993-07-16 00:43:42')
        ,(27,'tohara','Bret','Lesch','lowe.buck@example.net','ca249f05b3b37e81f6a423ceb11c6b47','1991-01-21 07:04:23')
        ,(28,'madge75','Maegan','Rippin','pbernier@example.org','5494ce336c46576cdc15126a7be33c98','1979-10-02 09:55:31')
        ,(29,'swaniawski.liam','Alford','Hintz','kozey.cortez@example.org','b10fb014927371efd45273d95d870073','2003-08-24 04:19:30')
        ,(30,'wromaguera','Betty','Fritsch','angelita.harvey@example.net','d355462624e40f8a37a1f98b56f88b10','2015-10-25 04:14:26')
        ,(31,'zackary68','Ryleigh','Corwin','vincenzo02@example.net','279abea7463ac0ca59676e4fae73a1e4','2007-03-28 10:08:08')
        ,(32,'angelo.bednar','Rowland','Hettinger','hterry@example.org','e24fd581303662312916181f1ce12d3a','1978-09-03 19:10:55')
        ,(33,'nharber','Lucious','Jones','schmitt.vincenzo@example.com','86d220bf64eb79a21d3405f4c1b52e69','2022-06-12 08:50:33')
        ,(34,'morgan.koch','Robyn','Boyer','vkilback@example.org','43e97b900be0888ad6c811d1785811ee','2009-04-01 09:32:34')
        ,(35,'king.triston','Vidal','Grimes','bednar.marjory@example.net','5e591a62922321d849bfc6d0c8770b1f','2015-07-03 06:37:25')
        ,(36,'margarete.pfeffe','Noah','DuBuque','lernser@example.org','354787678e819716056cf1e817013ac9','1991-11-14 05:55:38')
        ,(37,'madelynn.pfeffer','Valerie','Brown','gladys.mills@example.net','42627807b0669c8285666439e5e4bd82','1994-06-17 04:40:22')
        ,(38,'andrew.jones','Autumn','Cronin','konopelski.malinda@example.org','4c0e4abda18d39955f842db9a79ba4dd','1972-04-10 05:57:51')
        ,(39,'gislason.laisha','Macey','Nikolaus','maiya77@example.org','7643484702c04b56f07c7b3c7a650c7e','2013-06-04 01:17:58')
        ,(40,'bahringer.briell','Lesly','OReilly','eldridge49@example.net','fc0a4a7800a1352b50e4435b38ac0a3c','1976-05-04 18:27:23')
        ,(41,'urohan','Salma','Johnston','eli18@example.net','cb60c78811d948d3d083393474a03e24','2018-05-11 19:33:00')
        ,(42,'okuhn','Laverna','Pfannerstill','marcelino95@example.net','ebc75cf441438992962da379c50204b8','1991-07-14 20:57:51')
        ,(43,'lpagac','Idell','Johns','abshire.anastacio@example.com','11e6828e86148ceac028b2bc0697d843','1977-05-09 04:33:44')
        ,(44,'mohr.skylar','Rafael','Lemke','estevan74@example.org','4ab2509f979744af8bd1b3289c0f8f35','1976-06-18 19:28:02')
        ,(45,'steuber.kameron','Rahul','Kshlerin','xcorkery@example.com','42c37aa90e873091511be023cabad3a4','1986-07-27 05:43:20')
        ,(46,'buckridge.lexi','Ralph','Stroman','hiram36@example.com','766d6bb9517954acde7d99bcdd6ab6bd','1990-07-13 05:22:05')
        ,(47,'nova22','Angela','Prohaska','ezemlak@example.net','73024a7717634460c9d7af6ac23396c4','1990-11-03 23:37:58')
        ,(48,'glover.joaquin','Caleigh','Bartoletti','alana25@example.com','733a1e6f556aa14df811c9c5fd1405a9','1986-11-13 22:12:49')
        ,(49,'antonia07','Freida','White','qwyman@example.net','3d1696c74e2efd45267296f32c5718d0','2020-03-03 19:44:41')
        ,(50,'pbartell','Godfrey','Gaylord','lawrence56@example.org','0742d0380da64ddede11488f5048a8f2','1974-10-21 19:50:03')
        ,(51,'kacey.muller','Manley','Anderson','qkozey@example.org','34415d8acc6f58dc9b2a4653cc881c17','1975-04-15 13:41:36')
        ,(52,'mdavis','Kari','Lakin','purdy.chet@example.com','9f690829ba8491d8310615de75a3f4c3','1975-06-18 15:23:43')
        ,(53,'ashleigh15','Minerva','Cole','von.jeramie@example.org','de4e41546ac0f60f6fb8d353a8af9ec8','2020-11-23 06:36:11')
        ,(54,'bashirian.cathy','Kaela','Boehm','dannie81@example.org','4ffe77013ce99ff739c26e4880136ed7','1988-10-07 23:05:48')
        ,(55,'kory.braun','Sterling','Mayert','xgusikowski@example.com','b01b429bd519f84acc860552fb13caf9','1992-02-12 05:50:00')
        ,(56,'ericka22','Harmony','Hamill','jenkins.trey@example.com','82fae09196af659e41ea04de576888b7','1997-09-02 11:53:36')
        ,(57,'verla69','Clifton','Hirthe','cheyenne17@example.net','2cf3f0d0c80604b2ccaa8e11870e8787','2001-12-20 23:37:48')
        ,(58,'nelda.wilkinson','Lafayette','Buckridge','adolf63@example.com','8a79e28611231167847ab0fede47343e','1996-05-06 07:05:04')
        ,(59,'lela.bayer','Alexis','Brown','xkihn@example.org','7eb7b2ece5fd432965899831ecf1b976','1987-06-13 03:35:31')
        ,(60,'will.oleta','Rocio','Lakin','queenie92@example.net','0055a6cf9d382654f349b5cc299a964f','2001-09-16 00:46:16')
        ,(61,'broderick98','Eldred','McKenzie','ghessel@example.com','46f4dfe61db3882ac81288ab4db7a47a','1999-12-28 19:31:03')
        ,(62,'dietrich.carter','Shakira','Bogan','shanahan.clarissa@example.com','a276e5ba9dccbd7d5cc25735942de814','2007-02-27 09:33:58')
        ,(63,'silas38','Maurine','Spinka','miller.giuseppe@example.com','7870bb74a7504126d3d6461cef53f4af','2018-09-20 20:03:56')
        ,(64,'littel.randall','Tressa','Walsh','adrian16@example.com','0979f3bd7916cc4e236b11bb440df915','2008-09-03 19:02:25')
        ,(65,'quitzon.mireille','Helene','Senger','satterfield.margarett@example.net','e93c9986fa72a11b5c63cfd9215e02c3','1999-11-19 21:07:33')
        ,(66,'ofelia.stamm','Haven','Renner','noe90@example.net','42a5b908e3d1c1103316a69c1e74170c','1995-07-10 12:15:43')
        ,(67,'wisoky.veda','Jedidiah','Schumm','alyce.feil@example.com','77aa1c32575062f726897f243fa2b0a5','2002-05-27 11:10:00')
        ,(68,'gislason.ozella','Torrance','Murray','bjohnston@example.org','41a2a2629a4ccfa4c1b4a11d0e80c57f','1980-10-17 01:56:59')
        ,(69,'huels.chyna','Lawrence','Schimmel','cgoodwin@example.org','7609f6d5ff9f1901489392caf2408455','1996-05-13 17:03:59')
        ,(70,'lesch.gerard','Russell','Harber','tyrel61@example.org','d2a9358d0d3916fcadb71d2f79cf4dac','1987-12-20 22:12:08')
        ,(71,'andre.feest','Alessandra','Ruecker','lilliana91@example.net','8fde2d69ca6a71b629d86d71da510189','1995-10-11 08:30:01')
        ,(72,'larson.raoul','Maegan','Heidenreich','christiana.turcotte@example.com','7b44623d335a2319275143dd5261eb38','1972-09-09 05:52:36')
        ,(73,'manuel.zemlak','Lillie','Rutherford','aufderhar.gwendolyn@example.com','32425957a101515f5e67039a972b2f10','1978-04-05 00:40:07')
        ,(74,'klocko.max','Queen','Stark','malika.greenfelder@example.net','9d4543881502945a4e1dc104c849cf2d','2007-08-03 22:55:49')
        ,(75,'wellington15','Destin','DAmore','morris.runolfsdottir@example.net','af0f72f59fd0c4d3443632cee82b435d','1992-08-11 21:58:32')
        ,(76,'retta.kuvalis','Casandra','Murazik','jared.ohara@example.com','fe73b8d6b22ff4db8af020312b69ff34','1995-06-11 16:57:15')
        ,(77,'tad94','Nelle','Kiehn','obernier@example.org','3d01a9911e060be9770abcf29d0131ab','1970-11-24 17:29:03')
        ,(78,'lacy64','Vince','Brekke','eileen18@example.net','7d390758c2ee463c2d73269b2a234d9d','1981-10-17 03:47:51')
        ,(79,'dbernier','Nicklaus','Hoppe','amy.kutch@example.com','b00020d64a93176e40eba9a99872415d','1976-10-30 02:07:51')
        ,(80,'fbrown','Treva','Waelchi','durgan.ellis@example.org','3c9150c44b18ff87dfe02055463459c4','2006-03-14 12:59:04')
        ,(81,'bailee35','Lorenz','Larkin','kcormier@example.com','d61bfb85aaf51f5b224e4ded0b78a3a2','1981-01-23 08:38:14')
        ,(82,'leon.cruickshank','Madeline','Mann','caesar63@example.org','f866df74a30e8d44a9af706564850873','1976-04-07 08:28:29'),
        (83,'kessler.lysanne','Beth','Hirthe','uschamberger@example.com','19e0c34d4c530ce1b207adf3438be19c','1978-10-15 12:05:14')
        ,(84,'lraynor','Magnus','Hickle','sgleichner@example.net','70ae2d648968552fa3fe3985ef064705','2010-11-18 02:38:58')
        ,(85,'zkautzer','Ines','Fritsch','schmeler.elwin@example.com','317ff29ed424d5b8bcac3b8f28a973fe','2020-07-30 17:20:17')
        ,(86,'muller.nettie','Cade','Kuhic','marques.zieme@example.com','5c90bcfb412788af1d8193b3dd1adccf','1998-11-19 15:17:09'
        ,(87,'zieme.carole','Martina','DAmore','arvel.kiehn@example.org','83aabb17468407d0d7b2b364ea88415c','2011-08-08 19:57:15')
        ,(88,'woreilly','Cameron','Reichert','xkub@example.net','21a41bd72f74bc5339c697a1054e0bc8','1980-02-16 01:02:21')
        ,(89,'gerda.donnelly','Glenna','Hintz','atorphy@example.com','2bb8b5554834cbbae59c6719635c7068','1990-07-19 17:04:08')
        ,(90,'rath.caterina','Demetris','OKon','ullrich.oliver@example.org','e103adaffe54c30d1b9b4a24f38bb252','1981-07-01 04:30:46')
        ,(91,'emilia03','Keshawn','Schulist','vfay@example.com','fbed42ec715f4b93b5a3c237bbb1324b','1970-12-14 14:14:48')
        ,(92,'serena25','Serenity','Turcotte','glen34@example.org','1dc762e86658c96ad28a942c8b8b74cd','2007-08-10 10:58:36')
        ,(93,'mdonnelly','Alisha','Waters','royce32@example.net','1d29a4a8b23c7fcf585528764af90b95','2016-05-17 08:48:36')
        ,(94,'jayce53','Jesus','Jacobs','raegan99@example.org','1050fafc475241c5e43ebea9c489cc7b','1986-09-22 04:05:11')
        ,(95,'breitenberg.blan','General','Turcotte','destiney.stoltenberg@example.org','7cfdcea0411352796a80e9a02f51c29a','1997-07-09 21:35:43')
        ,(96,'alene43','Kathleen','Greenholt','narciso17@example.com','4c8909b6ba05cdd36053cb98f0b54b10','1979-06-02 09:35:28')
        ,(97,'milton.windler','Sylvia','Predovic','eduardo.rempel@example.net','b1cf54e002872838cff71aeb7dbfb3ad','1998-08-01 17:21:48')
        ,(98,'gerson91','Kiarra','Howe','breitenberg.lauriane@example.org','997512fd5d2c009c248483432d672512','1985-05-05 13:43:10')
        ,(99,'neffertz','Elyse','Ratke','ricky.feest@example.net','34b0adb68e8fc93aebc0fdb174ceb29d','1998-01-27 09:43:21')
        ,(100,'christina69','Jessyca','Aufderhar','ezekiel.bauch@example.net','5bba165c647dc200d09519e8b0282f79','1971-02-03 02:38:45')
        ,(101,'carmine.macejkov','Jett','Steuber','gleason.carolanne@example.com','7a4316d9d2dc4a354145e8e11e3e2a3c','2006-04-03 01:52:30')
        ,(102,'dwalsh','Vivienne','Lang','ddurgan@example.net','8b837e494729048f05b2daddf17c8d45','1972-10-26 01:31:28')
        ,(103,'bryon.flatley','Paxton','Cassin','brakus.cecilia@example.com','03572e9691e75b42d2e51e4c56695d2c','1983-01-22 23:07:04')
        ,(104,'purdy.montana','Eleanora','Koelpin','raven16@example.com','ba7a8f4da43cbc6bad5824269fd1911d','2007-12-02 06:57:42')
        ,(105,'rico.watsica','Margie','Durgan','paula.grady@example.com','9635cb8578df976bc7a3f9f2f10445d2','1986-05-22 14:23:00')
        ,(106,'satterfield.jess','Dale','Sporer','natalie.block@example.com','f52b549dbd52949ba750dc7e106eecd1','2013-05-22 20:02:03')
        ,(107,'jaiden90','Lewis','Sawayn','wisoky.aurelie@example.com','34284bff4ef0be77171114e4c9a5f3bb','2014-02-06 09:56:02')
        ,(108,'predovic.adrienn','Vinnie','Powlowski','domenica22@example.net','9904f6090562afcc3c362ee11edf1704','2011-12-09 03:26:34')
        ,(109,'victor05','Eda','Zieme','jeffrey48@example.com','f76b9f1be27395f001d63f5a8f2201fa','1980-08-25 16:15:06')
        ,(110,'nwalter','Aurore','Tromp','paxton.bauch@example.net','1fd3b85491575d35c71413209d0e8cc3','1972-04-26 09:45:26')
        ,(111,'treutel.marlon','Tristin','Hills','hermann.raymond@example.com','f51fec61b74e1c9628535ce0c7e3c2ac','1997-02-02 11:16:07')
        ,(112,'charlene.harber','Malika','Durgan','catalina55@example.net','23872e3e72212439ea916a73900fc4ad','2022-11-30 14:50:46')
        ,(113,'delbert63','Ansel','Goldner','shad03@example.net','814cdfdcbb53a1d58d090ce4e46cb057','2005-09-12 09:47:25')
        ,(114,'ullrich.marie','Raven','Hirthe','cameron.mayert@example.org','94cf056c3a6360b7db3407f029ec8742','1988-12-21 12:53:01')
        ,(115,'hudson.quitzon','Colin','Wiza','jspencer@example.net','aebb4061db1b4ac97459084c483eb198','2012-12-23 20:54:31')
        ,(116,'wauer','Lillian','Conroy','thea80@example.net','53e9fe97254cdfd3e0ded67d52e88037','2004-09-25 04:46:07')
        ,(117,'corwin.esperanza','Melody','Heidenreich','walter.maddison@example.com','ea1ec6326ee3ff0cabe25b2107738de1','2018-08-21 15:17:25')
        ,(118,'adriel93','Moriah','Strosin','alexa.grady@example.net','9470d325b497f9c21988a5cc887bef07','1980-04-11 13:03:20')
        ,(119,'abbie.heaney','Danial','Harris','faye.hermiston@example.org','c9b54100021a4ed80711c470cd0ab2f0','1987-10-06 18:24:26')
        ,(120,'maymie04','Meaghan','Kuhn','xbraun@example.org','696c13baed3fbcafbc3e4758a507398d','2006-04-17 17:37:40')
        ,(121,'abbott.eden','Pansy','Vandervort','coty.nienow@example.net','805e96ddc668febf6d3a3cff8045f5e2','1994-12-19 07:33:14')
        ,(122,'hodkiewicz.karia','Reta','Swaniawski','moore.ivory@example.org','558cb845ffab7428e30e9eab35e6d0a5','1998-08-09 18:58:35')
        ,(123,'hilda.jakubowski','Brooke','Hagenes','lindgren.maci@example.net','91d8816196b5c481d5fb8d8119e3b19c','1978-09-12 04:38:20')
        ,(124,'rosalind.carter','Jayne','Jacobi','goyette.beau@example.net','e0ce75fe105b29e329d7e76362c75daf','2006-04-21 01:12:10')
        ,(125,'ihintz','Kristopher','Marquardt','gottlieb.jaiden@example.org','9c348a12dbf543a439602d83087fc52e','2010-07-09 14:33:23')
        ,(126,'brooklyn96','Kameron','Robel','breanna.krajcik@example.com','bd00071f80cae5636c66f676b9f3144e','1972-04-06 00:24:58')
        ,(127,'thaddeus.howell','Holly','Treutel','zlabadie@example.com','4d07b6b73e9e4d5120bf330b6e858675','2006-07-10 05:57:35')
        ,(128,'noe64','Kurt','Connelly','kaylie16@example.com','c7518c147b3aaec0d124c8ea091a6ec6','2020-09-09 11:14:03')
        ,(129,'kessler.rose','Florida','Boehm','fgleason@example.net','a73173d2eb6a807ef3e6994b559c7d2a','2022-06-01 00:15:54')
        ,(130,'nichole63','Geo','Dickens','yasmin.predovic@example.net','1f82f62d153fe08da2b67365a142bad3','1987-08-21 04:49:19')
        ,(131,'noel29','Rocky','Armstrong','zoey.rowe@example.com','65a8ad5d5750b2e3071f6927ffabc62b','1979-06-14 03:37:20')
        ,(132,'jfriesen','Mike','Graham','zcormier@example.com','2e27bff33f3d57ce7421bd27d8b24eee','2017-04-20 20:53:18')
        ,(133,'sedrick.osinski','Katelin','Wehner','kmaggio@example.net','8209272e66cfb80a45d57a3fea3d7e89','1985-06-13 14:30:01')
        ,(134,'padberg.carter','Gwen','Greenholt','mmclaughlin@example.com','ec47792ade9aadb2776fa935db46748d','2019-10-06 18:37:19')
        ,(135,'devon06','Lelia','Mills','darian.nitzsche@example.org','11fe8d9d5ea04b24afaea135dbf9f478','1974-12-09 06:32:50')
        ,(136,'rokeefe','Garth','Walter','white.jesus@example.com','d3992964a0a830c06bc143a100aabaae','2013-01-22 16:59:45')
        ,(137,'goodwin.austen','Darien','Hilll','ttowne@example.com','ed6698207d5471fbd20b37924f7c038d','1997-09-22 09:37:37')
        ,(138,'parker66','Norris','Tromp','freddy74@example.org','60387c5dbfa0d742cedf98669e59bdcb','2009-03-07 16:56:21')
        ,(139,'brekke.maxwell','Lafayette','Kreiger','frances.berge@example.org','b5caa8caea61e3fc4242fdf6794b0baf','1996-10-09 17:17:30')
        ,(140,'zackery35','Trenton','Grady','vkunze@example.com','a6e690a4eac1d55e22e458a7e69c661c','2016-04-03 13:17:00')
        ,(141,'mcglynn.chance','Alessandra','Boyer','kautzer.stanford@example.org','e6a7fac43b8932893723f95e6729f3b6','1994-08-06 17:27:41')
        ,(142,'grace72','Bonita','Romaguera','gideon.bruen@example.com','d708c3d40c21e237e809104553c663ff','1994-06-14 18:53:26')
        ,(143,'katrina46','Allie','Stoltenberg','jarrett.larson@example.net','b599a83787253b4d757e9449eae140d7','2001-04-08 20:52:53')
        ,(144,'sienna56','Delilah','Sawayn','mschuppe@example.net','9bc689c0dfe906c0e78c5eef688e7fd4','2001-09-16 21:26:13')
        ,(145,'sheila97','Malcolm','Heller','grover.connelly@example.net','92e6b94f9fe0ea1b546a09ec3ff93381','2020-01-08 14:31:48')
        ,(146,'tristin08','Brianne','DuBuque','ljohns@example.com','e5f9d91fed8eb8ea6e0d183a42ee5a52','1981-05-03 19:30:48')
        ,(147,'luna23','Kade','Tromp','halvorson.elisa@example.org','289cf8ffaa1a865cf3a510121058b450','2016-07-24 05:07:32')
        ,(148,'ara81','Doris','Ruecker','delbert17@example.org','b9feeb0fc97d1e1abb67c3c79fc6cc47','2001-02-07 00:51:44')
        ,(149,'kristofer.bode','Stella','Streich','hegmann.emmalee@example.com','565d5e0038b9aa520484421aed2fc6ce','2004-02-23 18:33:56')
        ,(150,'goodwin.noelia','Antwon','Hilll','ladarius.skiles@example.org','f3d4b26adec7f7845746863a8a76aac1','2017-03-26 14:14:50')
        ,(151,'lynn.haley','Elouise','Stroman','purdy.fritz@example.org','714fc7b3ad5f7cc023b13838780aaff7','1998-03-28 12:09:34'
        ,(152,'chase65','Marcus','Becker','tmoen@example.com','8e2f51c49d6bed0c267bcbb8c1266896','1970-02-14 11:29:56')
        ,(153,'kmitchell','Trenton','Walsh','lgusikowski@example.org','40d34c1d03288a32ddc7eb7a71725912','2013-09-03 07:22:47')
        ,(154,'foster.bernier','Boyd','Lesch','magdalena.cole@example.com','8772b64ac2dd6b4c34c115873276b782','1985-03-22 22:02:23')
        ,(155,'lemke.palma','Ellsworth','DAmore','adoyle@example.com','5c726e5419a5bed580a1bfd167549b69','2005-12-03 21:59:57')
        ,(156,'heidenreich.emma','Sherman','Rohan','mziemann@example.org','20bb8285e3eaef5c4efc4f7ca87edd56','1991-11-23 16:10:31')
        ,(157,'cmueller','Hulda','Howe','beer.chance@example.com','ede7287a95e5d8e23dcb16f111d63867','2003-10-24 18:48:50')
        ,(158,'upfannerstill','June','Windler','keven.maggio@example.org','66a6446ec5a46303b95d55fd8486055d','1990-09-21 07:20:54')
        ,(159,'harber.haylee','Lazaro','Hackett','wschaden@example.org','5a33821c5a0229f88ae94bf35169e146','1989-05-14 17:51:55')
        ,(160,'alek44','Alan','Moen','hbernhard@example.net','ef28103f1590225a539d3ad6f305f293','2014-01-09 02:55:10')
        ,(161,'jamil.stoltenber','Jackeline','Wilkinson','ubeier@example.net','f13a9f672e4cd325de0b8d1549a288e2','1983-08-10 19:32:03')
        ,(162,'gleichner.zoila','Christ','Paucek','neal.kassulke@example.net','a4454a9ded5ce8a31084ed1db69c869b','2005-03-20 23:36:39')
        ,(163,'crona.kaycee','Kade','Pollich','sanford.hickle@example.com','2062ec5b995c6cdeea1b19cc3985a91d','2010-10-22 03:53:06')
        ,(164,'cornell64','Casandra','Ritchie','breitenberg.alfreda@example.net','d09d3682e8abe2e5e7440623eb466497','1996-07-29 11:21:25')
        ,(165,'judd.carroll','Brayan','Zemlak','vernie27@example.com','42842fd4aafb0d108472f5edf290110b','1989-08-13 10:46:17')
        ,(166,'kobe.dicki','Una','Weissnat','leopoldo69@example.org','a37b7c04b1145c127ecf43bb6462eb48','1983-01-26 02:46:53')
        ,(167,'jordi67','Fabiola','Bayer','dorothea.rolfson@example.org','b9d32812aae1a9cf19322f10a5c49a0c','1986-07-26 16:55:23')
        ,(168,'green.jacobi','Katlyn','Morissette','crona.kieran@example.net','5d1cebae46af3141d5f931060f67a2ee','2017-07-03 00:52:25')
        ,(169,'brayan.gleichner','Tom','Stroman','qbauch@example.com','ea4b576cf110db3d526f45e710eb0cf7','2004-08-26 21:12:28')
        ,(170,'pacocha.margaret','Ellsworth','Block','lennie33@example.net','3bbaf7c36016e56d9be35e64204ae466','2019-02-26 03:25:10')
        ,(171,'okon.kaylah','Daija','Smith','brando75@example.org','de49fcd181afa64f8d631588832d523c','1993-09-24 16:38:37')
        ,(172,'gzemlak','Queenie','Anderson','bfranecki@example.org','cd9bb859418f8387709a8b73001eca00','1997-12-07 03:09:24')
        ,(173,'adalberto75','Rebeka','Howell','uzemlak@example.net','7ffd93c67bccd1220278301c850c30b3','1983-07-19 08:12:24')
        ,(174,'ogottlieb','Delilah','Blanda','halle.pollich@example.com','b2d9d51aa22e15934a50e4210e7249f2','1977-01-26 19:22:45')
        ,(175,'ybins','Billy','Ankunding','crist.aliyah@example.com','2a44946a3414e8eb9bf4faddc7b4c012','1995-08-02 17:38:49')
        ,(176,'tate.huels','Alexandrine','Hartmann','xdooley@example.net','dc7665abe906aaecaf3215e03454f408','2022-02-22 08:54:07')
        ,(177,'owilliamson','Noble','Durgan','marvin.viviane@example.net','f9eb502c12ce9d1d5527771e0014c1bb','1977-05-25 20:01:05')
        ,(178,'clowe','Norene','Deckow','ratke.alva@example.net','73b772deb327189e31e021a2090dc6bc','1997-12-08 10:50:09')
        ,(179,'oschmeler','Kenyatta','Labadie','abshire.erik@example.org','e0c0571a09de9e3a7693f5ea1edc8312','1979-08-04 18:44:51')
        ,(180,'junius34','Belle','Wuckert','carter.terence@example.com','bb794b89a9d1a5de509efe30a81496e5','1997-01-16 13:31:56')
        ,(181,'tristian.towne','Jesse','Pouros','laury65@example.com','46d6a74871a127bbf088ec3979ad798e','2021-05-29 08:38:25')
        ,(182,'margarete.hansen','Ashly','Rutherford','hannah.little@example.net','9ea6d366f98cf42326691e024fba13d7','2022-12-09 23:09:56')
        ,(183,'roob.christop','Hilario','Johnston','sylvester.emmerich@example.com','8fef457f42a5473bcd57019c916ae92a','1985-06-29 22:54:17')
        ,(184,'travon50','Mavis','McClure','jasper.murray@example.org','2bfdab3827e23c3e1a1c5408aceb962a','2004-05-16 17:03:27')
        ,(185,'hyatt.amalia','Lesly','Stokes','reinger.earnest@example.org','b619d95a6b830bb89a0ee40378231221','2020-01-02 22:55:07')
        ,(186,'dell34','Matteo','Macejkovic','grant.aryanna@example.net','ec12458067ba83c98105e4832ff6a3ef','1986-09-10 16:15:21')
        ,(187,'kjacobs','Kelsie','Gulgowski','fisher.stacy@example.net','88a4ca59604664ff5bb1e047e6a95fe2','2006-09-14 00:44:52')
        ,(188,'lebsack.abbey','Millie','Rogahn','berry.ledner@example.com','29500af47552166ff435ad394dfcfe92','1981-04-01 23:41:24')
        ,(189,'spouros','Ryan','Luettgen','trent16@example.com','6d9470a7a3b827233850931ca644b9c8','2022-06-08 22:22:55')
        ,(190,'abner49','Kory','Schuppe','huel.daniella@example.com','4abb5e6232217c02798b4a9ce14264b6','1988-08-02 04:47:56')
        ,(191,'carter.vita','Emmanuel','Cummings','asia.upton@example.net','c4d829bacda9354984417c53b80ba169','2003-12-25 18:55:20')
        ,(192,'jacobs.louie','Hipolito','Lang','darius.gusikowski@example.org','c8a0f0223cce94b122ecfbf84e81a08a','2001-03-09 01:25:44')
        ,(193,'yhuel','Jermey','Berge','lpaucek@example.org','fb45b4341be43c8e9edf52846d828cae','1975-06-19 09:14:35')
        ,(194,'erdman.rhea','Kiera','Schulist','ronaldo31@example.com','5e14a498641633c3de2c214071371637','1993-10-08 17:20:31')
        ,(195,'grimes.dalton','Horace','Douglas','larson.phoebe@example.org','e814670a22173996fde8d7b86f32311a','2016-10-18 00:26:37')
        ,(196,'glover.myra','Alverta','Fahey','isaac61@example.org','8df30ff6c544279069dc509e22379c70','1992-08-20 14:37:35')
        ,(197,'abdullah.gibson','Curt','Swift','christine.kshlerin@example.org','722c2d943e4a4aa25e53ae49c1433553','1992-10-31 15:34:52')
        ,(198,'lelia.ullrich','Matilda','Prohaska','ashleigh07@example.net','226cd61fcba961e83db90da693f8fd6d','1997-06-12 08:24:50')
        ,(199,'jude.leffler','Octavia','Boyle','bradtke.reyna@example.net','ca7269825e487b41e6242e62245073df','1993-10-16 20:45:20')
        ,(200,'julius.predovic','Desiree','Kovacek','marian13@example.org','4ed3589e54b15301379751aaad7f979a','1980-10-20 15:29:02');
~~~

## `Table`

| `Name`   | `Comment`               | `Schema`           | `Engine` |
| :------- | :--------------------- | :------------------ | :------- |
| employee | The employee table.     | springa2023team6   | InnoDB   |

**When using the 'InnoDB' Relational Database Modeling Techniques(aka one pk per table), will be enforced**

## `Primary Key`

| `Columns` |
| :-------- |
| emp_no    |

## `Indexes`

## `Foreign Keys`

| `Columns` | `Ref Table` | `Ref Columns` | `Options` |
| --------- | ----------- | ------------- | --------- |
|           |             |               |           |

## `Columns`

| `Label`         | `Name`         | `Type`                                 | `Nullable` | `Default`           | `Comment`                    |
| :-------------- | :------------- | :------------------------------------- | :--------- | :------------------ | :--------------------------- |
| emp_no          | emp_no         | PK int auto_increment                  | `No`       |                     | Primary Key                  |
| username        | username       | varchar(16)                            | `No`       |                     | Login username               |
| first_name      | first_name     | varchar(14)                            | `No`       |                     | emp first name               |
| last_name       | last_name      | varchar(16)                            | `No`       |                     | emp last name                |
| email           | email          | varchar(255)                           | `Yes`      | ''                  | emp email                    |
| password        | password       | varchar(32)                            | `No`       |                     | Login password               |
| create_time     | create_time    | TIMESTAMP                              | `Yes`      | current_timestamp() | Time when record created     |
