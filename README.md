DarwinCoreExtraRanks
====================

Darwin Core Extra Ranks

DarwinCore ExtraRanks is a DarwinCore extension intended for atomization of taxon names in literature.
  	
		DarwinCore ExtraRanks provides elements for marking epithets of ranks that are not included in DarwinCore proper, and may not even be valid under the current nomenclature code, but used to be valid in the past and are thus common in legacy documents.
		
		In particular, it is intended to handle taxonomic names that have multiple infraspecific epithets or epithets of ranks between those DarwinCore has elements for, providing dedicated elements for all these ranks listed at http://code.google.com/p/darwincore/wiki/Taxon as valid values for the dwc:taxonRank element, and ones listed in http://rs.tdwg.org/UBIF/2006/Schema/1.1/UBIF_EnumLib.xsd.
		
		Epithets of ranks that DarwinCore has elements for are intended to be marked with these very element, the elements in this extension only fill in the gaps.
