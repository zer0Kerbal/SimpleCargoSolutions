// Changelog.cfg v1.0.0.0
// SimpleCargoSolutions by Axial Aerospace
// created: 2020 02 25
// updated: 2020 04 08

KERBALCHANGELOG
{
	showChangelog = True
	modName = SimpleCargoSolutions by Axial Aerospace
	license = LGPLv3
	author = artwhaley, zer0Kerbal
	VERSION
	{
		version = 1.1.99.0
		versionName = Brushing off the Construction Dust
		versionDate = 2021-09-19
		versionKSP = 1.12.2
		change = >>-- adopted for curation by @zer0Kerbal --<<
		change = <b><color=#BADA55>DO A CLEAN INSTALL: DELETE EXISTING THEN RE-INSTALL</color></b>
		change = <b>Resources and corresponding tanks have changed density/volume/cost/mass </b>
		CHANGE
		{
			type = Release
			change = for KSP 1.12.2
			subchange = won't be last release for 1.12.2
		}
		CHANGE
		{
			change = Localization
			subChange = added .this/Localization/
			subChange = added localization (en-us.cfg)
			subChange = adjusted phrasing a smudge
		}
		change = moved art into .this/Assets/
		change = updated texture pointers in model (original, png, dds included)
		change = updated part.cfg:
		change = added explosionPotential
		CHANGE
		{
			change = Changelog, .version, Readme.md
			subchange = created Changelog.cfg [KERBALCHANGELOG] (.this)
			subchange = Add license field
			subchange = Add author node
			subchange = Add version naming field
			subChange = added additional fields in .version (might need to tweak urls)
			subChange = added shields to Readme.md
		}
		CHANGE
		{
			change = Online
			subChange = GitHub Repo
			subChange = created Forum Thread
			subChange = updated SpaceDock
			subChange = updated CKAN/NetKAN
		}
		CHANGE
		{
			change = modernization, polish, update pass on .cfg
			subChange = large .tga -> .dds ( mb ->	mb)
			subChange = replaced mesh = with MODEL{}
			subChange = merged in patches
			subChange = automated deploy/release process
			subChange = adjusted nodes (flipped orientation as needed)
		}
		CHANGE
		{
			change = Adoption by zer0Kerbal
			subchange = Send Adoption Papers
			subChange = Post Adoption Notice
			subChange = gather
			subChange = verify licenses
			subChange = look for existing repo/postings
		}
	}
		CHANGE
		{
			change = organize for adoption
			subChange = folder structure
			subChange = added license(s) file(s)
			subChange = added .version file
			subChange = Readme
			subChange = automated backend
			subChange = jsons
			subChange = Changelog.md -> Kerbal Changelog Changelog.cfg
			subChange = updated Readme.md
			subChange = moved changelog into separate file
		}
	}
}

// GPLv2
// zer0Kerbal