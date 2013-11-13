	/* Itara */
	ExpPack.addPlatformItiraBackflash = function () {
		var icon = './mods/ExpansionPack/source/img/Itara.png';
		GDT.addPlatform(
			{
				id: '31102000-2-1-4-1-LINELIAR',
				name: 'Itara Backflash',
				company: 'Itara',
				startAmount: 1.3,
				unitsSold: 4.2,
				licencePrize: 150000,
				published: '1/1/1',
				platformRetireDate: '16/1/2',
				developmentCosts: 125000,
				genreWeightings: [0.8, 1, 0.6, 0.7, 1, 0.6],
				audienceWeightings: [0.8, 1, 0.7],
				techLevel: 2,
				iconUri: icon,
				events: [
					{
						id: '31102000-2-1-4-1-1-LINELIAR',
						date: '12/7/3',
						getNotification: function (company) {
							return new Notification({
								header: "Industry News".localize(),
								text: "Today Itara, a company known for their consoles in the early consolemarket, have announced that they're gonna release a new console called the Itara Backflash.{n} This console will compete with consoles like the TES. Itara has announced that they are anticipating the console to be very successfull.{n} The Itara Flashback is getting released in {0}.".localize().format(General.getETADescription('12/7/3', '12/11/3')),
								image: icon
							});
						}
					}
				]
			});
	};
	/*  */
	
	/* Ninvento */	
