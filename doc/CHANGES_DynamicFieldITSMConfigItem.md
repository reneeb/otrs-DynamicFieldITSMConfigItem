# Change log of DynamicFieldITSMConfigItem
* Copyright (C) 2006-2016 c.a.p.e. IT GmbH, http://www.cape-it.de/
* $Id: CHANGES_DynamicFieldITSMConfigItem.md,v 1.67 2016/12/20 12:48:19 tto Exp $

# 6.0.0 (2018/02/02)
* port module to OTRS6

# r5.0.6 (2017/12/20)
* (2016/12/20) - Bugfix: T2016122090002543 (Undefined subroutine in DynamicFieldITSMConfigItemAJAXHandler) (tto)
 
# r5.0.5 (2016/12/06)
* (2016/11/30) - Bugfix: T2016113090000671 (no results without constrictions in search) (millinger)
* (2016/10/07) - Bugfix: T2016100690000825 (added check of ITSMConfigItemClasses) (fjacquemin)
* (2016/09/06) - Bugfix: T2016080390000871 (merged changes from DFRemoteDB) (millinger)

# r5.0.4 (2016/09/05)
* (2016/08/30) - Bugfix: T2016082190000444 (changed layout of field to match conditions of KIX4OTRS) (millinger)
* (2016/08/30) - CR: (added selections for stats module) (millinger)
* (2016/07/26) - Bugfix: T2016072690000857 (failed to add value by script) (millinger)

# r5.0.3 (2016/06/30)
* (2016/06/30) - Bugfix: T2016063090000798 (edit field does not handle removed values correctly) (millinger)
* (2016/06/30) - Bugfix: T2016063090000798 (internal server error if constricted array value gets removed) (millinger)
* (2016/06/30) - Bugfix: T2016062990000693 (unescaped left brace in regexp is deprecated) (millinger)
* (2016/06/28) - Bugfix: T2016062890000766 (unnecessary ajax request triggered) (millinger)
* (2016/06/14) - Bugfix: T2016061390000721 (invalid argument type in push on migration) (millinger)
* (2016/05/30) - Bugfix: T2016053090000807 (MaxQueryResult is not used by ajaxhandler) (millinger)

# r5.0.2 (2016/04/22)
* (2016/04/20) - Bugfix: T2016022590000724 (can not use ticket template with mandatory field) (millinger)
* (2016/03/08) - Bugfix: (fixed undefined value as an ARRAY reference) (millinger)

# r5.0.1 (2016/02/29)
* (2016/02/29) - Bugfix: (mandatory fields were not marked correctly) (millinger)
* (2016/02/29) - Bugfix: (async ajax calls caused problems with running conditions) (millinger)

# r5.0.0 (2016/01/29)
* (2016/01/21) - Bugfix: T2016011890001221 (jobs of generic agents have to be checked on upgrade) (millinger)
* (2016/01/21) - Bugfix: T2016011890001221 (correct bind for autocomplete search in AdminGenericAgent) (millinger)

# r4.99.81 (2016/01/08)
* (2016/01/08) - CR: T2015082690000606 (Added trigger for removed values) (millinger)
* (2016/01/08) - CR: T2015082690000606 (Updated descriptions and translations) (millinger)
* (2016/01/08) - Bugfix: T2015082690000606 (Minor bugfixes) (millinger)

# r4.99.80 (2015/12/31)
* (2015/12/31) - CR: T2015082690000606 (reworked layout and handling) (millinger)
* (2015/12/31) - CR: T2015082690000606 (changes for use with 5.0.x) (millinger)

# r4.0.2 (2015/0?/??)
* (2015/07/14) - Bugfix: T2015071490000621 (inperformance in SearchFieldParameterBuild) (tto)

# r4.0.1 (2015/07/13)
* (2015/07/13) - Bugfix: T2015071390000383 (inperformance in DisplayValueRender) (tto)
* (2015/07/13) - CR: version number harmonization (match OTRS framework) (tto)
* (2015/04/16) - Bugfix: T2015041590000563 (fixed issues with empty values in ITSMConfigItemArray) (millinger)
* (2015/01/12) - Bugfix: T2015010890000242 (disabled preselected value in generic agent) (smehlig)
* (2014/12/08) - Bugfix: T2014102390001037 (<OTRS_TICKET_DynamicField_*_Value> doesn't work for CIRefArray DFs) (alitvinova)

# r1.2.0 (2014/12/01)
* (2014/12/01) - CR: T2014100890000307 (changes for use with OTRS 4.0.x) (alitvinova)

# r1.1.80 (2014/10/24)
* (2014/10/23) - Bugfix: T2014102390000931 (added sub StatsSearchFieldParameterBuild) (alitvinova)
* (2014/10/23) - Bugfix: T2014102390001064 (added sub ColumnFilterValuesGet) (alitvinova)
* (2014/10/23) - CR: T2014100890000307 (changes for use with OTRS 4.0.x) (alitvinova)

# r1.1.1 (2014/05/15)
* (2014/05/15) - Bugfix: T2014042990000842 (improved performance) (smehlig)
* (2014/04/02) - Bugfix: T2014040190000681 (fixed error on edit generic agent) (fober)
* (2013/11/18) - Bugfix: T2013111890000495 (fixed typo IsArrayhRefWithData) (altivinova)

# r1.1.0 (2013/11/14)
* (2013/11/14) - CR: T2013102190000231 (fixed makrer comments DFITSMCI) (tto)
* (2013/11/14) - Bugfix: (use DeploymentState filter from DF-configuration in CI-search) (tto)
* (2013/11/07) - CR: T2013102190000231 (added changes for OTRS 3.3.x) (smehlig)
* (2013/11/04) - Bugfix: T2013110490000431 (use replace placeholder function of OTRS) (smehlig)

# r1.0.0 (2013/11/04)
* (2013/11/04) - CR: T2013091690000261 (open link in new window) (smehlig)

# r0.5.1 (2013/10/21)
* (2013/10/21) - Bugfix: T2013091690000261 (array-support - removed syntax error) (smehlig)

# r0.5.0 (2013/10/21)
* (2013/10/21) - CR: T2013091690000261 (array-support - added links) (smehlig)
* (2013/10/21) - CR: T2013091690000261 (array-support - changed display of values) (smehlig)
* (2013/10/17) - CR: T2013091690000261 (added package install code frame) (tto)

# r0.4.0 (2013/10/10)
* (2013/10/10) - CR: T2013091690000261 (Added array-support) (smehlig)

# r0.3.1 (2013/10/08)
* (2013/10/08) - Bugfix: T2013091690000261 (code formatting) (smehlig)
* (2013/10/08) - Bugfix: T2013091690000261 (added package requirements) (smehlig)
* (2013/10/08) - Bugfix: T2013091690000261 (changed wrong description) (smehlig)

# r0.3.0 (2013/10/02)
* (2013/10/02) - CR: T2013091690000261 (added further information to package installation) (smehlig)
* (2013/10/02) - Bugfix: T2013091690000261 (improved config descriptions) (smehlig)
* (2013/10/02) - Bugfix: T2013091690000261 (changed default agent link - added placeholder) (smehlig)

# r0.2.0 (2013/10/01)
* (2013/10/01) - Bugfix: enable to set empty value in autocomplete (smehlig)
* (2013/10/01) - CR: T2013091690000261 (added customer link) (smehlig)
* (2013/10/01) - CR: T2013091690000261 (added config for display type) (smehlig)
* (2013/10/01) - CR: T2013091690000261 (added event to link ticket and CI) (smehlig)
* (2013/10/01) - CR: T2013091690000261 (added default link during field change) (smehlig)
* (2013/10/01) - CR: T2013091690000261 (removed option for translation) (smehlig)
* (2013/10/01) - CR: T2013091690000261 (added translations and guidelines) (smehlig)
* (2013/10/01) - CR: T2013091690000261 (moved changes file) (smehlig)

# r0.1.0 (2013/10/01)
* (2013/09/30) - CR: T2013091690000261 (create new dynamic field backend - config item reference) (smehlig)

