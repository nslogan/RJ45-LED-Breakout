# RJ45-LED-Breakout

## Description

Simple breakout board for an RJ45 with LEDs. Has two 0805 resistor pads tied to Vin with pins for LED1/2-. Has solder pads for both shield legs to optionally tie to ground. Intended for use with Amphenol RJHSE-548x series. You can find [this project on GitHub](https://github.com/nslogan/RJ45-LED-Breakout). Fits breadboard well with headers 0.9" apart.

## Production

The board measured 0.65x1.20in (17x30mm) and was designed for production at [OSH Park](https://www.oshpark.com/). The OSHPark DRU is located in the `res/` folder.

The boards can be purchased [here](https://www.oshpark.com/shared_projects/6Iadx5r2) @ $3.90 for three.

## Parts

All parts on this board are from the [LoganSmith-Eagle-Library](https://github.com/nslogan/LoganSmith-Eagle-Library) available on GitHub (work in progress).

The BOM is located in the release folder, all parts are sourced from Digi-Key.

## Project Structure

This project adheres to this structure:

	[ProjectName]
		README.md
		[release]
			[Major.Minor]
				ProjectName_BOM_Major.Minor.xls or ProjectName_BOM_BOM_Major.Minor.csv
				ProjectName_schematic_Major.Minor.pdf
				ProjectName_board-<top/mid#/bottom>_Major.Minor.png
				ProjectName_Major.Minor.sch
				ProjectName_Major.Minor.brd
				[Gerbers]
					...
			...
		[src]
			[Major.0]
				BoardName.sch
				BoardName.brd
				BOM.xls or BOM.csv
			[Major+1.0]
				...
			...
		[lib]
			...
		[res]
			Manufacturer.dru
			Manufacturer.cam