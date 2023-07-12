# Diabetic-Retinopathy
Transfer Learning for Diabetes Risk Assessment: "  Retinal Biomarkers for Diabetes Detection: Applying Deep Learning to Retinography Analysis  "
<html xmlns:v="urn:schemas-microsoft-com:vml"
xmlns:o="urn:schemas-microsoft-com:office:office"
xmlns:w="urn:schemas-microsoft-com:office:word"
xmlns:m="http://schemas.microsoft.com/office/2004/12/omml"
xmlns="http://www.w3.org/TR/REC-html40">

<head>

<meta name=ProgId content=Word.Document>
<meta name=Generator content="Microsoft Word 15">
<meta name=Originator content="Microsoft Word 15">
<link rel=File-List
href="file:///C:/Users/Rajat/AppData/Local/Temp/msohtmlclip1/01/clip_filelist.xml">
<link rel=Edit-Time-Data
href="file:///C:/Users/Rajat/AppData/Local/Temp/msohtmlclip1/01/clip_editdata.mso">
<!--[if !mso]>
<style>
v\:* {behavior:url(#default#VML);}
o\:* {behavior:url(#default#VML);}
w\:* {behavior:url(#default#VML);}
.shape {behavior:url(#default#VML);}
</style>
<![endif]--><!--[if gte mso 9]><xml>
 <o:OfficeDocumentSettings>
  <o:RelyOnVML/>
  <o:AllowPNG/>
 </o:OfficeDocumentSettings>
</xml><![endif]-->
<link rel=themeData
href="file:///C:/Users/Rajat/AppData/Local/Temp/msohtmlclip1/01/clip_themedata.thmx">
<link rel=colorSchemeMapping
href="file:///C:/Users/Rajat/AppData/Local/Temp/msohtmlclip1/01/clip_colorschememapping.xml">
<!--[if gte mso 9]><xml>
 <w:WordDocument>
  <w:View>Normal</w:View>
  <w:Zoom>0</w:Zoom>
  <w:TrackMoves>false</w:TrackMoves>
  <w:TrackFormatting/>
  <w:PunctuationKerning/>
  <w:ValidateAgainstSchemas/>
  <w:SaveIfXMLInvalid>false</w:SaveIfXMLInvalid>
  <w:IgnoreMixedContent>false</w:IgnoreMixedContent>
  <w:AlwaysShowPlaceholderText>false</w:AlwaysShowPlaceholderText>
  <w:DoNotPromoteQF/>
  <w:LidThemeOther>EN-US</w:LidThemeOther>
  <w:LidThemeAsian>X-NONE</w:LidThemeAsian>
  <w:LidThemeComplexScript>X-NONE</w:LidThemeComplexScript>
  <w:Compatibility>
   <w:BreakWrappedTables/>
   <w:SnapToGridInCell/>
   <w:WrapTextWithPunct/>
   <w:UseAsianBreakRules/>
   <w:DontGrowAutofit/>
   <w:SplitPgBreakAndParaMark/>
   <w:EnableOpenTypeKerning/>
   <w:DontFlipMirrorIndents/>
   <w:OverrideTableStyleHps/>
   <w:UseFELayout/>
  </w:Compatibility>
  <m:mathPr>
   <m:mathFont m:val="Cambria Math"/>
   <m:brkBin m:val="before"/>
   <m:brkBinSub m:val="&#45;-"/>
   <m:smallFrac m:val="off"/>
   <m:dispDef/>
   <m:lMargin m:val="0"/>
   <m:rMargin m:val="0"/>
   <m:defJc m:val="centerGroup"/>
   <m:wrapIndent m:val="1440"/>
   <m:intLim m:val="subSup"/>
   <m:naryLim m:val="undOvr"/>
  </m:mathPr></w:WordDocument>
</xml><![endif]--><!--[if gte mso 9]><xml>
 <w:LatentStyles DefLockedState="false" DefUnhideWhenUsed="false"
  DefSemiHidden="false" DefQFormat="false" DefPriority="99"
  LatentStyleCount="376">
  <w:LsdException Locked="false" Priority="0" QFormat="true" Name="Normal"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 1"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 2"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 3"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 4"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 5"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 6"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 7"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 8"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 9"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 6"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 7"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 8"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 9"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 1"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 2"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 3"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 4"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 5"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 6"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 7"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 8"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 9"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Normal Indent"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="footnote text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="annotation text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="header"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="footer"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index heading"/>
  <w:LsdException Locked="false" Priority="35" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="caption"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="table of figures"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="envelope address"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="envelope return"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="footnote reference"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="annotation reference"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="line number"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="page number"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="endnote reference"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="endnote text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="table of authorities"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="macro"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="toa heading"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number 5"/>
  <w:LsdException Locked="false" Priority="10" QFormat="true" Name="Title"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Closing"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Signature"/>
  <w:LsdException Locked="false" Priority="1" SemiHidden="true"
   UnhideWhenUsed="true" Name="Default Paragraph Font"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text Indent"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Message Header"/>
  <w:LsdException Locked="false" Priority="11" QFormat="true" Name="Subtitle"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Salutation"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Date"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text First Indent"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text First Indent 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Note Heading"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text Indent 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text Indent 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Block Text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Hyperlink"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="FollowedHyperlink"/>
  <w:LsdException Locked="false" Priority="22" QFormat="true" Name="Strong"/>
  <w:LsdException Locked="false" Priority="20" QFormat="true" Name="Emphasis"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Document Map"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Plain Text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="E-mail Signature"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Top of Form"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Bottom of Form"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Normal (Web)"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Acronym"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Address"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Cite"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Code"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Definition"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Keyboard"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Preformatted"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Sample"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Typewriter"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Variable"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Normal Table"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="annotation subject"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="No List"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Outline List 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Outline List 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Outline List 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Simple 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Simple 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Simple 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Classic 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Classic 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Classic 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Classic 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Colorful 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Colorful 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Colorful 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 6"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 7"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 8"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 6"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 7"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 8"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table 3D effects 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table 3D effects 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table 3D effects 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Contemporary"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Elegant"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Professional"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Subtle 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Subtle 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Web 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Web 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Web 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Balloon Text"/>
  <w:LsdException Locked="false" Priority="59" Name="Table Grid"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Theme"/>
  <w:LsdException Locked="false" SemiHidden="true" Name="Placeholder Text"/>
  <w:LsdException Locked="false" Priority="1" QFormat="true" Name="No Spacing"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 1"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 1"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 1"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 1"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 1"/>
  <w:LsdException Locked="false" SemiHidden="true" Name="Revision"/>
  <w:LsdException Locked="false" Priority="34" QFormat="true"
   Name="List Paragraph"/>
  <w:LsdException Locked="false" Priority="29" QFormat="true" Name="Quote"/>
  <w:LsdException Locked="false" Priority="30" QFormat="true"
   Name="Intense Quote"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 1"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 1"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 1"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 1"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 1"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 1"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 2"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 2"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 2"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 2"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 2"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 2"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 2"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 2"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 2"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 2"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 2"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 3"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 3"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 3"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 3"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 3"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 3"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 3"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 3"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 3"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 3"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 3"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 4"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 4"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 4"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 4"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 4"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 4"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 4"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 4"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 4"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 4"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 4"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 5"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 5"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 5"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 5"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 5"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 5"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 5"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 5"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 5"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 5"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 5"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 6"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 6"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 6"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 6"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 6"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 6"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 6"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 6"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 6"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 6"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 6"/>
  <w:LsdException Locked="false" Priority="19" QFormat="true"
   Name="Subtle Emphasis"/>
  <w:LsdException Locked="false" Priority="21" QFormat="true"
   Name="Intense Emphasis"/>
  <w:LsdException Locked="false" Priority="31" QFormat="true"
   Name="Subtle Reference"/>
  <w:LsdException Locked="false" Priority="32" QFormat="true"
   Name="Intense Reference"/>
  <w:LsdException Locked="false" Priority="33" QFormat="true" Name="Book Title"/>
  <w:LsdException Locked="false" Priority="37" SemiHidden="true"
   UnhideWhenUsed="true" Name="Bibliography"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="TOC Heading"/>
  <w:LsdException Locked="false" Priority="41" Name="Plain Table 1"/>
  <w:LsdException Locked="false" Priority="42" Name="Plain Table 2"/>
  <w:LsdException Locked="false" Priority="43" Name="Plain Table 3"/>
  <w:LsdException Locked="false" Priority="44" Name="Plain Table 4"/>
  <w:LsdException Locked="false" Priority="45" Name="Plain Table 5"/>
  <w:LsdException Locked="false" Priority="40" Name="Grid Table Light"/>
  <w:LsdException Locked="false" Priority="46" Name="Grid Table 1 Light"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark"/>
  <w:LsdException Locked="false" Priority="51" Name="Grid Table 6 Colorful"/>
  <w:LsdException Locked="false" Priority="52" Name="Grid Table 7 Colorful"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 1"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 1"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 1"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 1"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 1"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 1"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 2"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 2"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 2"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 2"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 2"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 2"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 3"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 3"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 3"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 3"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 3"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 3"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 4"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 4"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 4"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 4"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 4"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 4"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 5"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 5"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 5"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 5"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 5"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 5"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 6"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 6"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 6"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 6"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 6"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 6"/>
  <w:LsdException Locked="false" Priority="46" Name="List Table 1 Light"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark"/>
  <w:LsdException Locked="false" Priority="51" Name="List Table 6 Colorful"/>
  <w:LsdException Locked="false" Priority="52" Name="List Table 7 Colorful"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 1"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 1"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 1"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 1"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 1"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 1"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 2"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 2"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 2"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 2"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 2"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 2"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 3"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 3"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 3"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 3"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 3"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 3"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 4"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 4"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 4"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 4"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 4"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 4"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 5"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 5"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 5"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 5"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 5"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 5"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 6"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 6"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 6"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 6"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 6"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 6"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Mention"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Smart Hyperlink"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Hashtag"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Unresolved Mention"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Smart Link"/>
 </w:LatentStyles>
</xml><![endif]-->
<style>
<!--
 /* Font Definitions */
 @font-face
	{font-family:Wingdings;
	panose-1:5 0 0 0 0 0 0 0 0 0;
	mso-font-charset:2;
	mso-generic-font-family:auto;
	mso-font-pitch:variable;
	mso-font-signature:0 268435456 0 0 -2147483648 0;}
@font-face
	{font-family:Batang;
	panose-1:2 3 6 0 0 1 1 1 1 1;
	mso-font-alt:바탕;
	mso-font-charset:129;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:-1342176593 1775729915 48 0 524447 0;}
@font-face
	{font-family:"Cambria Math";
	panose-1:2 4 5 3 5 4 6 3 2 4;
	mso-font-charset:0;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:-536869121 1107305727 33554432 0 415 0;}
@font-face
	{font-family:Calibri;
	panose-1:2 15 5 2 2 2 4 3 2 4;
	mso-font-charset:0;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:-469750017 -1073732485 9 0 511 0;}
@font-face
	{font-family:"Calibri Light";
	panose-1:2 15 3 2 2 2 4 3 2 4;
	mso-font-charset:0;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:-469750017 -1073732485 9 0 511 0;}
@font-face
	{font-family:Cambria;
	panose-1:2 4 5 3 5 4 6 3 2 4;
	mso-font-charset:0;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:-536869121 1107305727 33554432 0 415 0;}
@font-face
	{font-family:"Book Antiqua";
	panose-1:2 4 6 2 5 3 5 3 3 4;
	mso-font-charset:0;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:647 0 0 0 159 0;}
@font-face
	{font-family:Aharoni;
	mso-font-charset:177;
	mso-generic-font-family:auto;
	mso-font-pitch:variable;
	mso-font-signature:2051 0 0 0 33 0;}
@font-face
	{font-family:Aldhabi;
	mso-font-charset:178;
	mso-generic-font-family:auto;
	mso-font-pitch:variable;
	mso-font-signature:-2147475449 -2147483648 8 0 65 0;}
@font-face
	{font-family:"Amasis MT Pro Medium";
	mso-font-charset:0;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:-1610612561 1073750107 0 0 147 0;}
@font-face
	{font-family:"Century Schoolbook";
	panose-1:2 4 6 4 5 5 5 2 3 4;
	mso-font-charset:0;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:647 0 0 0 159 0;}
@font-face
	{font-family:"Bahnschrift SemiCondensed";
	panose-1:2 11 5 2 4 2 4 2 2 3;
	mso-font-charset:0;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:-1610612025 2 0 0 415 0;}
@font-face
	{font-family:"Footlight MT Light";
	panose-1:2 4 6 2 6 3 10 2 3 4;
	mso-font-charset:0;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:3 0 0 0 1 0;}
@font-face
	{font-family:"Amasis MT Pro Black";
	mso-font-charset:0;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:-1610612561 1073750107 0 0 147 0;}
@font-face
	{font-family:"Bahnschrift Condensed";
	panose-1:2 11 5 2 4 2 4 2 2 3;
	mso-font-charset:0;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:-1610612025 2 0 0 415 0;}
@font-face
	{font-family:"Microsoft YaHei Light";
	panose-1:2 11 5 2 4 2 4 2 2 3;
	mso-font-charset:134;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:-2147483001 718209040 22 0 262175 0;}
@font-face
	{font-family:"Baskerville Old Face";
	panose-1:2 2 6 2 8 5 5 2 3 3;
	mso-font-charset:0;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:3 0 0 0 1 0;}
@font-face
	{font-family:"Agency FB";
	panose-1:2 11 5 3 2 2 2 2 2 4;
	mso-font-charset:0;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:3 0 0 0 1 0;}
@font-face
	{font-family:STXinwei;
	mso-font-charset:134;
	mso-generic-font-family:auto;
	mso-font-pitch:variable;
	mso-font-signature:1 135200768 16 0 262144 0;}
@font-face
	{font-family:"Berlin Sans FB Demi";
	panose-1:2 14 8 2 2 5 2 2 3 6;
	mso-font-charset:0;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:3 0 0 0 1 0;}
@font-face
	{font-family:"Segoe UI";
	panose-1:2 11 5 2 4 2 4 2 2 3;
	mso-font-charset:0;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:-469750017 -1073683329 9 0 511 0;}
@font-face
	{font-family:Roboto;
	mso-font-charset:0;
	mso-generic-font-family:auto;
	mso-font-pitch:variable;
	mso-font-signature:-536868097 1342185855 33 0 415 0;}
@font-face
	{font-family:"\@Microsoft YaHei Light";
	panose-1:2 11 5 2 4 2 4 2 2 3;
	mso-font-charset:134;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:-2147483001 718209040 22 0 262175 0;}
@font-face
	{font-family:"\@STXinwei";
	mso-font-charset:134;
	mso-generic-font-family:auto;
	mso-font-pitch:variable;
	mso-font-signature:1 135200768 16 0 262144 0;}
@font-face
	{font-family:"\@Batang";
	panose-1:2 3 6 0 0 1 1 1 1 1;
	mso-font-charset:129;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:-1342176593 1775729915 48 0 524447 0;}
 /* Style Definitions */
 p.MsoNormal, li.MsoNormal, div.MsoNormal
	{mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-parent:"";
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:8.0pt;
	margin-left:0cm;
	line-height:107%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:minor-fareast;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
h1
	{mso-style-priority:9;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-link:"Heading 1 Char";
	mso-style-next:Normal;
	margin-top:16.0pt;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:0cm;
	mso-pagination:widow-orphan lines-together;
	page-break-after:avoid;
	mso-outline-level:1;
	font-size:15.0pt;
	font-family:"Calibri Light",sans-serif;
	mso-ascii-font-family:"Calibri Light";
	mso-ascii-theme-font:major-latin;
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:major-fareast;
	mso-hansi-font-family:"Calibri Light";
	mso-hansi-theme-font:major-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:major-bidi;
	color:#2F5496;
	mso-themecolor:accent1;
	mso-themeshade:191;
	mso-font-kerning:0pt;
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;
	font-weight:normal;}
h3
	{mso-style-noshow:yes;
	mso-style-priority:9;
	mso-style-qformat:yes;
	mso-style-link:"Heading 3 Char";
	mso-style-next:Normal;
	margin-top:2.0pt;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:0cm;
	mso-pagination:widow-orphan lines-together;
	page-break-after:avoid;
	mso-outline-level:3;
	font-size:13.0pt;
	font-family:"Calibri Light",sans-serif;
	mso-ascii-font-family:"Calibri Light";
	mso-ascii-theme-font:major-latin;
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:major-fareast;
	mso-hansi-font-family:"Calibri Light";
	mso-hansi-theme-font:major-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:major-bidi;
	color:#538135;
	mso-themecolor:accent6;
	mso-themeshade:191;
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;
	font-weight:normal;}
p.MsoFooter, li.MsoFooter, div.MsoFooter
	{mso-style-priority:99;
	mso-style-link:"Footer Char";
	margin:0cm;
	mso-pagination:widow-orphan;
	tab-stops:center 234.0pt right 468.0pt;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:minor-fareast;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
a:link, span.MsoHyperlink
	{mso-style-priority:99;
	color:#0563C1;
	mso-themecolor:hyperlink;
	text-decoration:underline;
	text-underline:single;}
a:visited, span.MsoHyperlinkFollowed
	{mso-style-noshow:yes;
	mso-style-priority:99;
	color:#954F72;
	mso-themecolor:followedhyperlink;
	text-decoration:underline;
	text-underline:single;}
p
	{mso-style-priority:99;
	mso-margin-top-alt:auto;
	margin-right:0cm;
	mso-margin-bottom-alt:auto;
	margin-left:0cm;
	mso-pagination:widow-orphan;
	font-size:12.0pt;
	font-family:"Times New Roman",serif;
	mso-fareast-font-family:"Times New Roman";}
p.MsoListParagraph, li.MsoListParagraph, div.MsoListParagraph
	{mso-style-priority:34;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:8.0pt;
	margin-left:36.0pt;
	mso-add-space:auto;
	line-height:107%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:minor-fareast;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
p.MsoListParagraphCxSpFirst, li.MsoListParagraphCxSpFirst, div.MsoListParagraphCxSpFirst
	{mso-style-priority:34;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-type:export-only;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:36.0pt;
	mso-add-space:auto;
	line-height:107%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:minor-fareast;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
p.MsoListParagraphCxSpMiddle, li.MsoListParagraphCxSpMiddle, div.MsoListParagraphCxSpMiddle
	{mso-style-priority:34;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-type:export-only;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:36.0pt;
	mso-add-space:auto;
	line-height:107%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:minor-fareast;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
p.MsoListParagraphCxSpLast, li.MsoListParagraphCxSpLast, div.MsoListParagraphCxSpLast
	{mso-style-priority:34;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-type:export-only;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:8.0pt;
	margin-left:36.0pt;
	mso-add-space:auto;
	line-height:107%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:minor-fareast;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
span.Heading1Char
	{mso-style-name:"Heading 1 Char";
	mso-style-priority:9;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-link:"Heading 1";
	mso-ansi-font-size:15.0pt;
	mso-bidi-font-size:15.0pt;
	font-family:"Calibri Light",sans-serif;
	mso-ascii-font-family:"Calibri Light";
	mso-ascii-theme-font:major-latin;
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:major-fareast;
	mso-hansi-font-family:"Calibri Light";
	mso-hansi-theme-font:major-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:major-bidi;
	color:#2F5496;
	mso-themecolor:accent1;
	mso-themeshade:191;}
span.Heading3Char
	{mso-style-name:"Heading 3 Char";
	mso-style-noshow:yes;
	mso-style-priority:9;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-link:"Heading 3";
	mso-ansi-font-size:13.0pt;
	mso-bidi-font-size:13.0pt;
	font-family:"Calibri Light",sans-serif;
	mso-ascii-font-family:"Calibri Light";
	mso-ascii-theme-font:major-latin;
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:major-fareast;
	mso-hansi-font-family:"Calibri Light";
	mso-hansi-theme-font:major-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:major-bidi;
	color:#538135;
	mso-themecolor:accent6;
	mso-themeshade:191;}
span.FooterChar
	{mso-style-name:"Footer Char";
	mso-style-priority:99;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-link:Footer;}
.MsoChpDefault
	{mso-style-type:export-only;
	mso-default-props:yes;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:minor-fareast;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-font-kerning:0pt;
	mso-ligatures:none;
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
.MsoPapDefault
	{mso-style-type:export-only;
	margin-bottom:8.0pt;
	line-height:107%;}
@page WordSection1
	{size:595.3pt 841.9pt;
	margin:34.0pt 34.0pt 34.0pt 34.0pt;
	mso-header-margin:35.4pt;
	mso-footer-margin:35.4pt;
	border:double #44546A 2.5pt;
	mso-border-themecolor:text2;
	mso-border-alt:triple #44546A 2.5pt;
	mso-border-themecolor:text2;
	padding:13.0pt 12.0pt 13.0pt 12.0pt;
	mso-paper-source:0;}
div.WordSection1
	{page:WordSection1;}
 /* List Definitions */
 @list l0
	{mso-list-id:263266056;
	mso-list-type:hybrid;
	mso-list-template-ids:1716706794 518297768 1074331673 1074331675 1074331663 1074331673 1074331675 1074331663 1074331673 1074331675;}
@list l0:level1
	{mso-level-suffix:none;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:17.4pt;
	text-indent:18.0pt;}
@list l0:level2
	{mso-level-number-format:alpha-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:89.4pt;
	text-indent:-18.0pt;}
@list l0:level3
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	margin-left:125.4pt;
	text-indent:-9.0pt;}
@list l0:level4
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:161.4pt;
	text-indent:-18.0pt;}
@list l0:level5
	{mso-level-number-format:alpha-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:197.4pt;
	text-indent:-18.0pt;}
@list l0:level6
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	margin-left:233.4pt;
	text-indent:-9.0pt;}
@list l0:level7
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:269.4pt;
	text-indent:-18.0pt;}
@list l0:level8
	{mso-level-number-format:alpha-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:305.4pt;
	text-indent:-18.0pt;}
@list l0:level9
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	margin-left:341.4pt;
	text-indent:-9.0pt;}
@list l1
	{mso-list-id:359866661;
	mso-list-type:hybrid;
	mso-list-template-ids:-2000243664 978111506 -1 -1 -1 -1 -1 -1 -1 -1;}
@list l1:level1
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:25.05pt;
	text-indent:-18.0pt;
	mso-ansi-font-size:20.0pt;
	mso-bidi-font-size:20.0pt;
	mso-ansi-font-weight:bold;
	mso-bidi-font-weight:bold;}
@list l1:level2
	{mso-level-number-format:alpha-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l1:level3
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	text-indent:-9.0pt;}
@list l1:level4
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l1:level5
	{mso-level-number-format:alpha-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l1:level6
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	text-indent:-9.0pt;}
@list l1:level7
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l1:level8
	{mso-level-number-format:alpha-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l1:level9
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	text-indent:-9.0pt;}
@list l2
	{mso-list-id:497112658;
	mso-list-type:hybrid;
	mso-list-template-ids:-1296127500 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653;}
@list l2:level1
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l2:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l2:level3
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l2:level4
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l2:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l2:level6
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l2:level7
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l2:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l2:level9
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l3
	{mso-list-id:934246280;
	mso-list-type:hybrid;
	mso-list-template-ids:1411127750 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653;}
@list l3:level1
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l3:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l3:level3
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l3:level4
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l3:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l3:level6
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l3:level7
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l3:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l3:level9
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l4
	{mso-list-id:1959946662;
	mso-list-type:hybrid;
	mso-list-template-ids:-1514116808 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653;}
@list l4:level1
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l4:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l4:level3
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l4:level4
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l4:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l4:level6
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l4:level7
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l4:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l4:level9
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l5
	{mso-list-id:1989049324;
	mso-list-template-ids:-814327500;}
@list l5:level1
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l5:level2
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l5:level3
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l5:level4
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l5:level5
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l5:level6
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l5:level7
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l5:level8
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l5:level9
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
ol
	{margin-bottom:0cm;}
ul
	{margin-bottom:0cm;}
-->
</style>
<!--[if gte mso 10]>
<style>
 /* Style Definitions */
 table.MsoNormalTable
	{mso-style-name:"Table Normal";
	mso-tstyle-rowband-size:0;
	mso-tstyle-colband-size:0;
	mso-style-noshow:yes;
	mso-style-priority:99;
	mso-style-parent:"";
	mso-padding-alt:0cm 5.4pt 0cm 5.4pt;
	mso-para-margin-top:0cm;
	mso-para-margin-right:0cm;
	mso-para-margin-bottom:8.0pt;
	mso-para-margin-left:0cm;
	line-height:107%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
table.MsoTableGrid
	{mso-style-name:"Table Grid";
	mso-tstyle-rowband-size:0;
	mso-tstyle-colband-size:0;
	mso-style-priority:59;
	mso-style-unhide:no;
	border:solid windowtext 1.0pt;
	mso-border-alt:solid windowtext .5pt;
	mso-padding-alt:0cm 5.4pt 0cm 5.4pt;
	mso-border-insideh:.5pt solid windowtext;
	mso-border-insidev:.5pt solid windowtext;
	mso-para-margin:0cm;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-ansi-language:EN-US;
	mso-fareast-language:EN-US;}
</style>
<![endif]--><!--[if gte mso 9]><xml>
 <o:shapedefaults v:ext="edit" spidmax="1217"/>
</xml><![endif]--><!--[if gte mso 9]><xml>
 <o:shapelayout v:ext="edit">
  <o:idmap v:ext="edit" data="1"/>
  <o:rules v:ext="edit">
   <o:r id="V:Rule1" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_1024518725"/>
   <o:r id="V:Rule2" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_1336974171"/>
   <o:r id="V:Rule3" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_1440304990"/>
   <o:r id="V:Rule4" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_461608603"/>
   <o:r id="V:Rule5" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_454461926"/>
   <o:r id="V:Rule6" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_1320931215"/>
   <o:r id="V:Rule7" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_1769667104"/>
   <o:r id="V:Rule8" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_1200085525"/>
   <o:r id="V:Rule9" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_895770943"/>
   <o:r id="V:Rule10" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_109421316"/>
   <o:r id="V:Rule11" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_2091286855"/>
   <o:r id="V:Rule12" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_1359995866"/>
   <o:r id="V:Rule13" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_1705028141">
    <o:proxy end="" idref="#Oval_x0020_1295694585" connectloc="2"/>
   </o:r>
   <o:r id="V:Rule14" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_2049054085"/>
   <o:r id="V:Rule15" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_1414357924">
    <o:proxy start="" idref="#Rectangle_x0020_1972155111" connectloc="2"/>
   </o:r>
   <o:r id="V:Rule16" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_319506377">
    <o:proxy start="" idref="#Rectangle_x0020_676510769" connectloc="2"/>
    <o:proxy end="" idref="#Oval_x0020_1295694585" connectloc="1"/>
   </o:r>
   <o:r id="V:Rule17" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_790501659"/>
   <o:r id="V:Rule18" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_24968267"/>
   <o:r id="V:Rule19" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_648634280">
    <o:proxy end="" idref="#Oval_x0020_1295694585" connectloc="7"/>
   </o:r>
   <o:r id="V:Rule20" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_1112665680">
    <o:proxy start="" idref="#Rectangle_x0020_618536290" connectloc="2"/>
   </o:r>
   <o:r id="V:Rule21" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_352065956">
    <o:proxy start="" idref="#Rectangle_x0020_1117822195" connectloc="2"/>
   </o:r>
   <o:r id="V:Rule22" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_144327271">
    <o:proxy start="" idref="#Rectangle_x0020_1791994478" connectloc="2"/>
    <o:proxy end="" idref="#Oval_x0020_1295694585" connectloc="6"/>
   </o:r>
   <o:r id="V:Rule23" type="connector" idref="#Straight_x0020_Connector_x0020_885235549"/>
   <o:r id="V:Rule24" type="connector" idref="#Connector_x003a__x0020_Elbow_x0020_10"/>
   <o:r id="V:Rule25" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_11"/>
   <o:r id="V:Rule26" type="connector" idref="#Connector_x003a__x0020_Elbow_x0020_13"/>
   <o:r id="V:Rule27" type="connector" idref="#Connector_x003a__x0020_Elbow_x0020_9"/>
   <o:r id="V:Rule28" type="connector" idref="#Connector_x003a__x0020_Elbow_x0020_12"/>
   <o:r id="V:Rule29" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_624902139"/>
   <o:r id="V:Rule30" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_264841957"/>
   <o:r id="V:Rule31" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_1190690328"/>
   <o:r id="V:Rule32" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_1989385050"/>
   <o:r id="V:Rule33" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_872971181">
    <o:proxy end="" idref="#Oval_x0020_783565083" connectloc="2"/>
   </o:r>
   <o:r id="V:Rule34" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_1460317106">
    <o:proxy end="" idref="#Oval_x0020_1148904216" connectloc="2"/>
   </o:r>
   <o:r id="V:Rule35" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_1597942042">
    <o:proxy start="" idref="#Rectangle_x0020_1722699284" connectloc="2"/>
    <o:proxy end="" idref="#Oval_x0020_1674420311" connectloc="3"/>
   </o:r>
   <o:r id="V:Rule36" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_602706592">
    <o:proxy end="" idref="#Oval_x0020_117885256" connectloc="3"/>
   </o:r>
   <o:r id="V:Rule37" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_415267197">
    <o:proxy end="" idref="#Oval_x0020_1547476610" connectloc="2"/>
   </o:r>
   <o:r id="V:Rule38" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_1179713348"/>
   <o:r id="V:Rule39" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_784849400"/>
   <o:r id="V:Rule40" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_1900142344"/>
   <o:r id="V:Rule41" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_1903017055"/>
   <o:r id="V:Rule42" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_1840073957"/>
   <o:r id="V:Rule43" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_1253926772"/>
   <o:r id="V:Rule44" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_322792122">
    <o:proxy start="" idref="#Oval_x0020_783565083" connectloc="6"/>
    <o:proxy end="" idref="#Oval_x0020_537120086" connectloc="2"/>
   </o:r>
   <o:r id="V:Rule45" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_2017575650">
    <o:proxy start="" idref="#Oval_x0020_1148904216" connectloc="6"/>
    <o:proxy end="" idref="#Oval_x0020_182230772" connectloc="1"/>
   </o:r>
   <o:r id="V:Rule46" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_1356770645">
    <o:proxy end="" idref="#Oval_x0020_537120086" connectloc="2"/>
   </o:r>
   <o:r id="V:Rule47" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_239619105">
    <o:proxy end="" idref="#Oval_x0020_182230772" connectloc="1"/>
   </o:r>
   <o:r id="V:Rule48" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_1103943478">
    <o:proxy start="" idref="#Oval_x0020_1148904216" connectloc="6"/>
   </o:r>
   <o:r id="V:Rule49" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_281018422">
    <o:proxy start="" idref="#Oval_x0020_117885256" connectloc="6"/>
    <o:proxy end="" idref="#Oval_x0020_537120086" connectloc="2"/>
   </o:r>
   <o:r id="V:Rule50" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_384200251">
    <o:proxy end="" idref="#Oval_x0020_182230772" connectloc="1"/>
   </o:r>
   <o:r id="V:Rule51" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_1803323194">
    <o:proxy start="" idref="#Oval_x0020_1547476610" connectloc="7"/>
   </o:r>
   <o:r id="V:Rule52" type="connector" idref="#Straight_x0020_Arrow_x0020_Connector_x0020_1658828820"/>
   <o:r id="V:Rule53" type="connector" idref="#Straight_x0020_Connector_x0020_2028385560">
    <o:proxy start="" idref="#Rectangle_x0020_1240736954" connectloc="0"/>
   </o:r>
   <o:r id="V:Rule54" type="connector" idref="#Straight_x0020_Connector_x0020_1526957993">
    <o:proxy start="" idref="#Rectangle_x0020_1240736954" connectloc="2"/>
   </o:r>
   <o:r id="V:Rule55" type="connector" idref="#Straight_x0020_Connector_x0020_1714650020">
    <o:proxy start="" idref="#Rectangle_x0020_25672909" connectloc="0"/>
   </o:r>
   <o:r id="V:Rule56" type="connector" idref="#Straight_x0020_Connector_x0020_1987843476">
    <o:proxy start="" idref="#Rectangle_x0020_25672909" connectloc="2"/>
   </o:r>
  </o:rules>
 </o:shapelayout></xml><![endif]-->
</head>

<body lang=EN-IN link="#0563C1" vlink="#954F72" style='tab-interval:36.0pt;
word-wrap:break-word'>
<!--StartFragment-->

<p class=MsoNormal style='line-height:normal'><a name="_top"></a><u
style='text-underline:black;mso-text-underline-themecolor:text1'><span
lang=EN-US style='font-size:26.0pt;font-family:"Book Antiqua",serif;mso-bidi-font-family:
Aldhabi;mso-style-textoutline-type:none;mso-style-textoutline-outlinestyle-dpiwidth:
0pt;mso-style-textoutline-outlinestyle-linecap:flat;mso-style-textoutline-outlinestyle-join:
round;mso-style-textoutline-outlinestyle-pctmiterlimit:0%;mso-style-textoutline-outlinestyle-dash:
solid;mso-style-textoutline-outlinestyle-align:center;mso-style-textoutline-outlinestyle-compound:
simple;mso-style-textfill-type:gradient;mso-style-textfill-fill-gradientfill-shadetype:
linear;mso-style-textfill-fill-gradientfill-shade-linearshade-angle:5400000;
mso-style-textfill-fill-gradientfill-shade-linearshade-fscaled:no;mso-style-textfill-fill-gradientfill-stoplist:
"0 \#1F4E79 8 100000 lumm=50000\,50000 \#5B9BD5 8 100000\,100000 \#9DC3E6 8 100000 lumm=60000 lumo=40000";
mso-effects-reflection-dpiradius:.5pt;mso-effects-reflection-dpidistance:0pt;
mso-effects-reflection-angdirection:5400000;mso-effects-reflection-pctsx:100.0%;
mso-effects-reflection-pctsy:-90.0%;mso-effects-reflection-anglekx:0;
mso-effects-reflection-angleky:0;mso-effects-reflection-pctalphastart:53.0%;
mso-effects-reflection-pctstartpos:0%;mso-effects-reflection-pctalphaend:.3%;
mso-effects-reflection-pctendpos:35.5%;mso-effects-reflection-angfadedirection:
5400000;mso-effects-reflection-align:bottomleft;mso-bidi-font-weight:bold'>Transfer
Learning for Diabetes Risk <o:p></o:p></span></u></p>

<p class=MsoNormal><u style='text-underline:black;mso-text-underline-themecolor:
text1'><span lang=EN-US style='font-size:26.0pt;line-height:107%;font-family:
"Book Antiqua",serif;mso-bidi-font-family:Aldhabi;mso-style-textoutline-type:
none;mso-style-textoutline-outlinestyle-dpiwidth:0pt;mso-style-textoutline-outlinestyle-linecap:
flat;mso-style-textoutline-outlinestyle-join:round;mso-style-textoutline-outlinestyle-pctmiterlimit:
0%;mso-style-textoutline-outlinestyle-dash:solid;mso-style-textoutline-outlinestyle-align:
center;mso-style-textoutline-outlinestyle-compound:simple;mso-style-textfill-type:
gradient;mso-style-textfill-fill-gradientfill-shadetype:linear;mso-style-textfill-fill-gradientfill-shade-linearshade-angle:
5400000;mso-style-textfill-fill-gradientfill-shade-linearshade-fscaled:no;
mso-style-textfill-fill-gradientfill-stoplist:"0 \#1F4E79 8 100000 lumm=50000\,50000 \#5B9BD5 8 100000\,100000 \#9DC3E6 8 100000 lumm=60000 lumo=40000";
mso-effects-reflection-dpiradius:.5pt;mso-effects-reflection-dpidistance:0pt;
mso-effects-reflection-angdirection:5400000;mso-effects-reflection-pctsx:100.0%;
mso-effects-reflection-pctsy:-90.0%;mso-effects-reflection-anglekx:0;
mso-effects-reflection-angleky:0;mso-effects-reflection-pctalphastart:53.0%;
mso-effects-reflection-pctstartpos:0%;mso-effects-reflection-pctalphaend:.3%;
mso-effects-reflection-pctendpos:35.5%;mso-effects-reflection-angfadedirection:
5400000;mso-effects-reflection-align:bottomleft;mso-bidi-font-weight:bold'>Assessment:</span></u><span
lang=EN-US style='font-size:28.0pt;line-height:107%;font-family:"Book Antiqua",serif;
mso-bidi-font-family:Aldhabi;mso-style-textoutline-type:none;mso-style-textoutline-outlinestyle-dpiwidth:
0pt;mso-style-textoutline-outlinestyle-linecap:flat;mso-style-textoutline-outlinestyle-join:
round;mso-style-textoutline-outlinestyle-pctmiterlimit:0%;mso-style-textoutline-outlinestyle-dash:
solid;mso-style-textoutline-outlinestyle-align:center;mso-style-textoutline-outlinestyle-compound:
simple;mso-style-textfill-type:gradient;mso-style-textfill-fill-gradientfill-shadetype:
linear;mso-style-textfill-fill-gradientfill-shade-linearshade-angle:5400000;
mso-style-textfill-fill-gradientfill-shade-linearshade-fscaled:no;mso-style-textfill-fill-gradientfill-stoplist:
"0 \#1F4E79 8 100000 lumm=50000\,50000 \#5B9BD5 8 100000\,100000 \#9DC3E6 8 100000 lumm=60000 lumo=40000";
mso-effects-reflection-dpiradius:.5pt;mso-effects-reflection-dpidistance:0pt;
mso-effects-reflection-angdirection:5400000;mso-effects-reflection-pctsx:100.0%;
mso-effects-reflection-pctsy:-90.0%;mso-effects-reflection-anglekx:0;
mso-effects-reflection-angleky:0;mso-effects-reflection-pctalphastart:53.0%;
mso-effects-reflection-pctstartpos:0%;mso-effects-reflection-pctalphaend:.3%;
mso-effects-reflection-pctendpos:35.5%;mso-effects-reflection-angfadedirection:
5400000;mso-effects-reflection-align:bottomleft;mso-bidi-font-weight:bold'> </span><b><span
lang=EN-US style='font-size:24.0pt;line-height:107%;font-family:"Book Antiqua",serif;
color:black;mso-themecolor:text1'>&quot;</span></b><span lang=EN-US> <span
style='mso-spacerun:yes'> </span></span><b><span lang=EN-US style='font-size:
24.0pt;line-height:107%;font-family:"Book Antiqua",serif;color:black;
mso-themecolor:text1'>Retinal Biomarkers for Diabetes<span
style='mso-spacerun:yes'>               </span><span style='mso-tab-count:4'>                       </span><span
style='mso-spacerun:yes'>    </span>Detection: Applying Deep <span
style='mso-tab-count:3'>                 </span><span style='mso-tab-count:
2'>            </span><span style='mso-spacerun:yes'>          </span>Learning
to Retinography <span style='mso-spacerun:yes'>   </span><span
style='mso-tab-count:5'>                              </span><span
style='mso-spacerun:yes'>    </span>Analysis<span style='mso-spacerun:yes'> 
</span>&quot;<o:p></o:p></span></b></p>

<p class=MsoNormal style='text-align:justify;text-justify:inter-ideograph'><b><span
lang=EN-US style='font-size:18.0pt;line-height:107%;font-family:"Book Antiqua",serif;
mso-bidi-font-family:Aldhabi'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><v:rect id="Rectangle_x0020_4" o:spid="_x0000_s1216"
 style='position:absolute;margin-left:181.4pt;margin-top:2.4pt;width:189.6pt;
 height:159.2pt;z-index:-1895824384;visibility:visible;mso-wrap-style:square;
 mso-width-percent:0;mso-height-percent:0;mso-wrap-distance-left:9pt;
 mso-wrap-distance-top:0;mso-wrap-distance-right:9pt;
 mso-wrap-distance-bottom:0;mso-position-horizontal:absolute;
 mso-position-horizontal-relative:margin;mso-position-vertical:absolute;
 mso-position-vertical-relative:text;mso-width-percent:0;mso-height-percent:0;
 mso-width-relative:margin;mso-height-relative:margin;v-text-anchor:middle'
 o:gfxdata="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
I5S0/QkMjeEySiB2hPrmQjSA45aR5OkLf5XMknAht5AIU4PrpJNmg4hIzD1Koravtl+4gcY6h2jd
qquQED5a5dYgrXxsyoHTbSfjyQSPpOl2g6Isnd5Chk9zhfOpZr86WHGyKbi7H45PvCGd8ocIQqzR
qioDjomAs4Nqas0xgcOwIpGV8TdXmLK0a55G6RhK6YgmIcoqipnMU7hO5YU6+q6wgXGX7RkMapgk
K4TDQBVY06hWNS2qRqrD0qp7PpOynJE0y5ppZRVVNd1ZzFohLwNztrxakTe0yk0MOc2s8Gnqnk+5
a3mum+sTiioBBi/s56i6FygIhmrlYpZqSuPFNKxydka1a0e+wXNUu0iRMLJ+Mxc7Z7eiRjiXA+KV
Kj/wzUctkCZ5X6kt7TrY3kOJNwyqbR8Ol2E4+Ayu4HjaB9qqoq0qGlzBmTOUi/SguO1nFzkFnqeU
AlPLKbUcU88p9ZzSyCmNnNLMKU3f0yeqcIqvDlN9Lz8whRqWHbBmvYV9+r/xLwAAAP//AwBQSwME
FAAGAAgAAAAhAJxmRkG7AAAAJAEAACoAAABjbGlwYm9hcmQvZHJhd2luZ3MvX3JlbHMvZHJhd2lu
ZzEueG1sLnJlbHOEj80KwjAQhO+C7xD2btJ6EJEmvYjQq9QHCMk2LTY/JFHs2xvoRUHwsjCz7Dez
TfuyM3liTJN3HGpaAUGnvJ6c4XDrL7sjkJSl03L2DjksmKAV201zxVnmcpTGKSRSKC5xGHMOJ8aS
GtHKRH1AVzaDj1bmIqNhQaq7NMj2VXVg8ZMB4otJOs0hdroG0i+hJP9n+2GYFJ69elh0+UcEy6UX
FqCMBjMHSldnnTUtXYGJhn39Jt4AAAD//wMAUEsBAi0AFAAGAAgAAAAhALvlSJQFAQAAHgIAABMA
AAAAAAAAAAAAAAAAAAAAAFtDb250ZW50X1R5cGVzXS54bWxQSwECLQAUAAYACAAAACEArTA/8cEA
AAAyAQAACwAAAAAAAAAAAAAAAAA2AQAAX3JlbHMvLnJlbHNQSwECLQAUAAYACAAAACEAL+QoTIkC
AADqBQAAHwAAAAAAAAAAAAAAAAAgAgAAY2xpcGJvYXJkL2RyYXdpbmdzL2RyYXdpbmcxLnhtbFBL
AQItABQABgAIAAAAIQCSfYfgHQcAAEkgAAAaAAAAAAAAAAAAAAAAAOYEAABjbGlwYm9hcmQvdGhl
bWUvdGhlbWUxLnhtbFBLAQItABQABgAIAAAAIQCcZkZBuwAAACQBAAAqAAAAAAAAAAAAAAAAADsM
AABjbGlwYm9hcmQvZHJhd2luZ3MvX3JlbHMvZHJhd2luZzEueG1sLnJlbHNQSwUGAAAAAAUABQBn
AQAAPg0AAAAA
" fillcolor="white [3201]" strokecolor="black [3200]" strokeweight="1pt">
 <w:wrap anchorx="margin"/>
</v:rect><v:shapetype id="_x0000_t75" coordsize="21600,21600" o:spt="75"
 o:preferrelative="t" path="m@4@5l@4@11@9@11@9@5xe" filled="f" stroked="f">
 <v:stroke joinstyle="miter"/>
 <v:formulas>
  <v:f eqn="if lineDrawn pixelLineWidth 0"/>
  <v:f eqn="sum @0 1 0"/>
  <v:f eqn="sum 0 0 @1"/>
  <v:f eqn="prod @2 1 2"/>
  <v:f eqn="prod @3 21600 pixelWidth"/>
  <v:f eqn="prod @3 21600 pixelHeight"/>
  <v:f eqn="sum @0 0 1"/>
  <v:f eqn="prod @6 1 2"/>
  <v:f eqn="prod @7 21600 pixelWidth"/>
  <v:f eqn="sum @8 21600 0"/>
  <v:f eqn="prod @7 21600 pixelHeight"/>
  <v:f eqn="sum @10 21600 0"/>
 </v:formulas>
 <v:path o:extrusionok="f" gradientshapeok="t" o:connecttype="rect"/>
 <o:lock v:ext="edit" aspectratio="t"/>
</v:shapetype><v:shape id="Picture_x0020_1" o:spid="_x0000_s1215" type="#_x0000_t75"
 alt="A picture containing text, poster, graphic design, graphics&#10;&#10;Description automatically generated"
 style='position:absolute;margin-left:206.05pt;margin-top:.35pt;width:142.4pt;
 height:146.35pt;z-index:251658240;visibility:visible;mso-wrap-style:square;
 mso-width-percent:0;mso-height-percent:0;mso-wrap-distance-left:9pt;
 mso-wrap-distance-top:0;mso-wrap-distance-right:9pt;
 mso-wrap-distance-bottom:0;mso-position-horizontal:absolute;
 mso-position-horizontal-relative:margin;mso-position-vertical:absolute;
 mso-position-vertical-relative:text;mso-width-percent:0;mso-height-percent:0;
 mso-width-relative:margin;mso-height-relative:margin'>
 <v:imagedata src="file:///C:/Users/Rajat/AppData/Local/Temp/msohtmlclip1/01/clip_image001.png"
  o:title="A picture containing text, poster, graphic design, graphics&#10;&#10;Description automatically generated"/>
 <w:wrap type="square" anchorx="margin"/>
</v:shape><span lang=EN-US style='font-size:18.0pt;line-height:107%;font-family:
"Book Antiqua",serif;mso-bidi-font-family:Aldhabi'><o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:18.0pt;line-height:107%;
font-family:"Book Antiqua",serif;mso-bidi-font-family:Aldhabi'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:18.0pt;line-height:107%;
font-family:"Book Antiqua",serif;mso-bidi-font-family:Aldhabi'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:18.0pt;line-height:107%;
font-family:"Book Antiqua",serif;mso-bidi-font-family:Aldhabi'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:18.0pt;line-height:107%;
font-family:"Book Antiqua",serif;mso-bidi-font-family:Aldhabi'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:18.0pt;line-height:107%;
font-family:"Book Antiqua",serif;mso-bidi-font-family:Aldhabi'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:16.0pt;line-height:107%;
font-family:"Cambria",serif;mso-bidi-font-family:Aldhabi'>Authors- <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:16.0pt;line-height:107%;
font-family:"Cambria",serif;mso-bidi-font-family:Aldhabi'><span
style='mso-spacerun:yes'> </span><span style='mso-spacerun:yes'> </span><span
style='mso-spacerun:yes'>  </span><span style='mso-tab-count:1'>      </span>Rajat
Chakraborty<span style='mso-spacerun:yes'>              </span></span><span
lang=EN-US style='font-size:14.0pt;line-height:107%;font-family:"Cambria",serif;
mso-bidi-font-family:Aldhabi'><span style='mso-spacerun:yes'>  </span>Email: <a
href="mailto:rajatchakrabortyofficial@gmail.com">rajatchakrabortyofficial@gmail.com</a></span><span
lang=EN-US style='font-size:16.0pt;line-height:107%;font-family:"Cambria",serif;
mso-bidi-font-family:Aldhabi'><o:p></o:p></span></p>

<h3 style='mso-line-height-alt:15.0pt;background:white'><span lang=EN-US
style='font-size:16.0pt;font-family:"Cambria",serif;mso-bidi-font-family:Aldhabi'><span
style='mso-spacerun:yes'>  </span><span style='mso-spacerun:yes'>  </span><span
style='mso-tab-count:1'>      </span></span><span lang=EN-US style='font-size:
16.0pt;font-family:"Cambria",serif;mso-bidi-font-family:Aldhabi;color:black;
mso-themecolor:text1'>Snehashis Sadhukhan<span style='mso-spacerun:yes'>  
</span><span style='mso-spacerun:yes'> </span><span
style='mso-spacerun:yes'>    </span></span><span lang=EN-US style='font-size:
14.0pt;font-family:"Cambria",serif;mso-bidi-font-family:Aldhabi;color:black;
mso-themecolor:text1'>Email: <span style='mso-spacerun:yes'> </span><span
style='mso-spacerun:yes'> </span>snehasishsadhukhan2016@gmail.com</span><span
lang=EN-US style='font-family:Roboto;color:#5F6368'><o:p></o:p></span></h3>

<p class=MsoNormal><span lang=EN-US style='font-size:16.0pt;line-height:107%;
font-family:"Cambria",serif;mso-bidi-font-family:Aldhabi'><span
style='mso-spacerun:yes'> </span></span><span lang=EN-US style='font-size:16.0pt;
line-height:107%;font-family:"Book Antiqua",serif;mso-bidi-font-family:Aldhabi'><o:p></o:p></span></p>

<p class=MsoNormal><b><span lang=EN-US style='font-size:16.0pt;line-height:
107%;font-family:"Cambria",serif;mso-bidi-font-family:Aldhabi'>Guided by–<o:p></o:p></span></b></p>

<p class=MsoNormal style='margin-left:72.0pt'><b><span lang=EN-US
style='font-size:18.0pt;line-height:107%;font-family:"Cambria",serif;
mso-bidi-font-family:Aldhabi'>Anupam Sen<o:p></o:p></span></b></p>

<p class=MsoNormal style='margin-left:72.0pt'><b><span lang=EN-US
style='font-size:18.0pt;line-height:107%;font-family:"Cambria",serif;
mso-bidi-font-family:Aldhabi'>Assistant Professor<o:p></o:p></span></b></p>

<p class=MsoNormal style='margin-left:72.0pt'><b><span lang=EN-US
style='font-size:18.0pt;line-height:107%;font-family:"Cambria",serif;
mso-bidi-font-family:Aldhabi'>Department of Computer Science,<o:p></o:p></span></b></p>

<p class=MsoNormal style='margin-left:72.0pt'><b><span lang=EN-US
style='font-size:18.0pt;line-height:107%;font-family:"Cambria",serif;
mso-bidi-font-family:Aldhabi'>Government General Degree College, Singur<o:p></o:p></span></b></p>

<p class=MsoNormal style='margin-left:252.0pt'><b><span lang=EN-US
style='font-size:30.0pt;line-height:107%;font-family:"Book Antiqua",serif;
mso-bidi-font-family:Aharoni;color:#2F5496;mso-themecolor:accent1;mso-themeshade:
191'><span style='mso-spacerun:yes'> </span><o:p></o:p></span></b></p>

<p class=MsoNormal style='margin-left:252.0pt'><b><span lang=EN-US
style='font-size:30.0pt;line-height:107%;font-family:"Book Antiqua",serif;
mso-bidi-font-family:Aharoni;color:#2F5496;mso-themecolor:accent1;mso-themeshade:
191'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal style='margin-left:252.0pt'><b><span lang=EN-US
style='font-size:30.0pt;line-height:107%;font-family:"Book Antiqua",serif;
mso-bidi-font-family:Aharoni;color:#2F5496;mso-themecolor:accent1;mso-themeshade:
191'><span style='mso-spacerun:yes'> </span></span></b><b><u><span lang=EN-US
style='font-size:30.0pt;line-height:107%;font-family:"Book Antiqua",serif;
mso-bidi-font-family:Aharoni;color:black;mso-themecolor:text1'>Table of
contents</span></u></b><b><u><span lang=EN-US style='font-size:30.0pt;
line-height:107%;font-family:"Book Antiqua",serif;mso-bidi-font-family:Aharoni'><o:p></o:p></span></u></b></p>

<p class=MsoNormal align=center style='margin-left:18.0pt;text-align:center'><b><span
lang=EN-US style='font-size:26.0pt;line-height:107%;font-family:"Book Antiqua",serif;
mso-bidi-font-family:Aharoni'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal align=center style='margin-left:18.0pt;text-align:center'><b><span
lang=EN-US style='font-size:26.0pt;line-height:107%;font-family:"Book Antiqua",serif;
mso-bidi-font-family:Aharoni'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal align=center style='margin-left:18.0pt;text-align:center'><b><span
lang=EN-US style='font-size:26.0pt;line-height:107%;font-family:"Book Antiqua",serif;
mso-bidi-font-family:Aharoni'><o:p>&nbsp;</o:p></span></b></p>



Sr. no. | Topic | Page no.
-- | -- | --
1 | Abstract | 3
2 | Introduction | 4-5
3 | Related Work | 6
4 | Deep Learning | 7
5 | Convolutional Neural   Network | 8
6 | Transfer Learning Algorithms | 9
7 | Data Set | 10-11
8 | Proposed Methodology | 12
9 | Evaluation Matrices | 13
10 | Results and Analysis | 14-16
11 | Conclusion | 17
12 | Future Work | 18
13 | Reference | 19
  |   |  
  |   |  
  |   |  



<p class=MsoNormal><b><span lang=EN-US style='font-size:18.0pt;line-height:
107%;font-family:"Cambria",serif;mso-bidi-font-family:Aldhabi'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoNormal><span lang=EN-US style='font-size:13.0pt;line-height:107%;
font-family:"Times New Roman",serif;color:black;mso-color-alt:windowtext;
background:white'>The python libraries such as TensorFlow </span><span
lang=EN-US><a href="https://www.tensorflow.org/guide"><b><span
style='font-size:13.0pt;line-height:107%;font-family:"Times New Roman",serif;
background:white'>[</span></b><b><span style='font-size:13.0pt;line-height:
107%;font-family:"Times New Roman",serif'>9<span style='background:white'>]</span></span></b></a></span><span
lang=EN-US style='font-size:13.0pt;line-height:107%;font-family:"Times New Roman",serif;
color:black;mso-color-alt:windowtext;background:white'> and keras Tuner </span><span
lang=EN-US><a href="https://keras.io/api/applications/%5d"><b><span
style='font-size:13.0pt;line-height:107%;font-family:"Times New Roman",serif;
background:white'>[</span></b><b><span style='font-size:13.0pt;line-height:
107%;font-family:"Times New Roman",serif'>10<span style='background:white'>]</span></span></b></a></span><b><span
lang=EN-US style='font-size:13.0pt;line-height:107%;font-family:"Times New Roman",serif;
color:black;mso-color-alt:windowtext;background:white'> </span></b><span
lang=EN-US style='font-size:13.0pt;line-height:107%;font-family:"Times New Roman",serif;
color:black;mso-color-alt:windowtext;background:white'>are used to implement the
models in this study. In the code we have imported the datasets of fundus
images</span><span style='font-size:13.0pt;line-height:107%;font-family:"Times New Roman",serif;
color:black;mso-color-alt:windowtext;background:white;mso-ansi-language:EN-IN'>
and augmented them. To overcome Overfitting, We have used some regularization
methods for augmentation we have used zoomed scale and rotated the images. When
we feed the images to the transfer learning models and fit the model with our
data set</span><span lang=EN-US style='font-size:13.0pt;line-height:107%;
font-family:"Times New Roman",serif'>.</span><span style='font-size:13.0pt;
line-height:107%;font-family:"Times New Roman",serif;mso-ansi-language:EN-IN'>
Then find validation accuracy validation loss along with training accuracy
training loss. From the confusion matrix we have found precision recall then by
calculation f1 score</span><span lang=EN-US style='font-size:13.0pt;line-height:
107%;font-family:"Times New Roman",serif'><o:p></o:p></span></p>

<p class=MsoNormal><span style='font-size:13.0pt;line-height:107%;font-family:
"Times New Roman",serif;mso-ansi-language:EN-IN'>We had 5 different fundus
image classes, we have separated them or partitioned then into 2 classes for
binary classification.</span><span lang=EN-US style='font-size:13.0pt;
line-height:107%;font-family:"Times New Roman",serif'><o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:13.0pt;line-height:107%;
font-family:"Times New Roman",serif'>By augmentation the </span><span
style='font-size:13.0pt;line-height:107%;font-family:"Times New Roman",serif;
mso-ansi-language:EN-IN'>Number of images increased above 5000 from <span
style='mso-spacerun:yes'> </span>3663. We have selected 64 as the batch size.
And the number of epochs is fixed to 25. Our main goal was To have higher test
accuracy, training accuracy, and validation accuracy. Although in the medical
field image classification. The recall is more important than anything else. Almost
Maximum of models have minimum of<span style='mso-spacerun:yes'>  </span>90% of
recall. <o:p></o:p></span></p>

<p class=MsoNormal><span style='font-size:13.0pt;line-height:107%;font-family:
"Times New Roman",serif;mso-ansi-language:EN-IN'>Almost maximum of our models
predicted 95 out of 100 images correctly. our goal was to achieve lower
validation loss and higher recall value. vgg 16, vgg 19 models Got<span
style='mso-spacerun:yes'>  </span>95% of validation accuracy .Resnet models
have identified diabetic retinopathy very well. Resnet models have good test accuracy,
recall, precision, and f1 score. Dense net models with 121 layers r also very
effective eat has second Louis training loss and the lowest validation laws
with highest validation accuracy along with lowest test loss. Dense net models
worked very well in diabetic retinopathy fundus image classification. It also has
97.39% of test accuracy 97.43% of precision 97.29% of recall and 97.35% of F1 score.</span><b><span
lang=EN-US style='font-size:13.0pt;line-height:107%;font-family:"Times New Roman",serif'><o:p></o:p></span></b></p>

<p class=MsoNormal style='margin-left:360.0pt'><b><u><span lang=EN-US
style='font-size:48.0pt;line-height:107%;font-family:"Cambria",serif;
mso-bidi-font-family:Aldhabi'>C</span></u></b><b><u><span lang=EN-US
style='font-size:28.0pt;line-height:107%;font-family:"Cambria",serif;
mso-bidi-font-family:Aldhabi'>onclusion<o:p></o:p></span></u></b></p>

<p class=MsoNormal><v:shape id="Arrow_x003a__x0020_Bent_x0020_2" o:spid="_x0000_s1026"
 style='position:absolute;margin-left:-14.1pt;margin-top:27.15pt;width:16.1pt;
 height:14.2pt;z-index:251714560;visibility:visible;mso-wrap-style:square;
 mso-wrap-distance-left:9pt;mso-wrap-distance-top:0;mso-wrap-distance-right:9pt;
 mso-wrap-distance-bottom:0;mso-position-horizontal:absolute;
 mso-position-horizontal-relative:text;mso-position-vertical:absolute;
 mso-position-vertical-relative:text;v-text-anchor:middle' coordsize="204537,180474"
 o:gfxdata="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
" path="m,180474l,101517c,57910,35350,22560,78957,22560r80462,-1l159419,r45118,45119l159419,90237r,-22559l78957,67678v-18689,,-33839,15150,-33839,33839c45118,127836,45119,154155,45119,180474l,180474xe"
 fillcolor="#4472c4 [3204]" strokecolor="#09101d [484]" strokeweight="1pt">
 <v:stroke joinstyle="miter"/>
 <v:path arrowok="t" o:connecttype="custom" o:connectlocs="0,180474;0,101517;78957,22560;159419,22559;159419,0;204537,45119;159419,90237;159419,67678;78957,67678;45118,101517;45119,180474;0,180474"
  o:connectangles="0,0,0,0,0,0,0,0,0,0,0,0"/>
</v:shape><b><span lang=EN-US style='font-size:16.0pt;line-height:107%;
font-family:"Cambria",serif;mso-bidi-font-family:Aldhabi'><o:p>&nbsp;</o:p></span></b></p>

<br style='mso-ignore:vglayout' clear=ALL>

<p class=MsoNormal style='text-align:justify;text-justify:inter-ideograph;
line-height:150%'><span lang=EN-US style='font-size:14.0pt;line-height:150%;
font-family:"Times New Roman",serif'><span style='mso-spacerun:yes'>  
</span>For our project we take the help of Google Colaboratory . We use the <b>Tesla
T4</b> GPU , . 24 GB of DDR5 Ram and 110 GB of storage to run our codes. <o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;text-justify:inter-ideograph;
line-height:150%'><span lang=EN-US style='font-size:14.0pt;line-height:150%;
font-family:"Times New Roman",serif;color:#222222;background:white'>This study
investigated the performance of Ten distinct transfer learning models .</span><span
lang=EN-US style='font-size:10.0pt;line-height:150%;font-family:"Arial",sans-serif;
color:#222222;background:white'> </span><span lang=EN-US style='font-size:14.0pt;
line-height:150%;font-family:"Times New Roman",serif;color:#222222;background:
white'>with preprocessing and data augmentation approaches, In this study we
got encouraging findings on our DR classification .</span><span lang=EN-US
style='font-size:14.0pt;line-height:150%;font-family:"Times New Roman",serif'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpFirst style='text-align:justify;text-justify:inter-ideograph;
text-indent:-18.0pt;line-height:150%;mso-list:l4 level1 lfo6'><![if !supportLists]><span
lang=EN-US style='font-size:14.0pt;line-height:150%;font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-size:14.0pt;
line-height:150%;font-family:"Times New Roman",serif'>Overall ,among the 9
metrics <b>Resnet</b></span><span lang=EN-US style='font-size:16.0pt;
line-height:150%;font-family:"Times New Roman",serif'> </span><b><span
lang=EN-US style='font-size:14.0pt;line-height:150%;font-family:"Times New Roman",serif'>152</span></b><span
lang=EN-US style='font-size:16.0pt;line-height:150%;font-family:"Times New Roman",serif'>
</span><b><span lang=EN-US style='font-size:14.0pt;line-height:150%;font-family:
"Times New Roman",serif'>V2</span></b><span lang=EN-US style='font-size:16.0pt;
line-height:150%;font-family:"Times New Roman",serif'><span
style='mso-spacerun:yes'>  </span></span><span lang=EN-US style='font-size:
14.0pt;line-height:150%;font-family:"Times New Roman",serif'>has higher
performance in 6 of them.<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpLast style='text-align:justify;text-justify:inter-ideograph;
line-height:150%'><span lang=EN-US style='font-size:14.0pt;line-height:150%;
font-family:"Times New Roman",serif'>It has a training accuracy of <b>98.60 %</b>
, lowest training loss of 0.0817 ,highest test accuracy of <b>98.34%,</b>
precision of <b>98.74%</b> , Recall of <b>97.67%</b> ,<span
style='mso-spacerun:yes'>  </span>F1 score<span style='mso-spacerun:yes'> 
</span>of <b>98.20%</b> . So as of now <b>Resnet 152 v2</b><span
style='mso-spacerun:yes'>  </span>model<span style='mso-spacerun:yes'> 
</span>is on top. In the second <span style='mso-spacerun:yes'> </span>we found
the model <b>DenseNet121.</b>It has got <b>97.43%</b> Training accuracy ,and
lowest validation loss <b>0.0733.</b> , High Test accuracy of <b>97.39%</b> <span
style='mso-spacerun:yes'> </span>and great f1 score of <span
style='mso-spacerun:yes'> </span><b>97.35%<span style='mso-spacerun:yes'> 
</span>.</b><o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;text-justify:inter-ideograph'><span
lang=EN-US style='font-size:14.0pt;line-height:107%;font-family:"Times New Roman",serif'><span
style='mso-spacerun:yes'> </span><span style='mso-tab-count:2'>                   </span><span
style='mso-spacerun:yes'> </span>Other Inception Models<span
style='mso-spacerun:yes'>  </span>and ResNet Models also performed well.<span
style='mso-spacerun:yes'>  </span><b>EfficientNetB0</b> was the lowest scorer.</span><span
lang=EN-US style='font-size:10.0pt;line-height:107%;font-family:"Times New Roman",serif;
color:black'> </span><span lang=EN-US style='font-size:14.0pt;line-height:107%;
font-family:"Times New Roman",serif;color:black'>InceptionV3 has scored<span
style='mso-spacerun:yes'>   </span><b>96.68%</b> of test accuracy,<span
style='mso-spacerun:yes'>  </span></span><span lang=EN-US style='font-size:
14.0pt;line-height:107%;font-family:"Times New Roman",serif'><o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;text-justify:inter-ideograph'><span
lang=EN-US style='font-size:14.0pt;line-height:107%;font-family:"Times New Roman",serif;
color:black'>I<b>nceptionResnetV2</b> scored<b> <span
style='mso-spacerun:yes'>  </span>96.58%</b> <b>, mobilenetV2</b> scored<b><span
style='mso-spacerun:yes'>  </span>96.53%</b> of test accuracy.</span><span
lang=EN-US style='font-size:20.0pt;line-height:107%;font-family:"Times New Roman",serif'><o:p></o:p></span></p>

<p class=MsoNormal><b><span lang=EN-US style='font-size:14.0pt;line-height:
107%;font-family:"Times New Roman",serif'>So overall Resnet 152 V2 worked best
for our dataset.<o:p></o:p></span></b></p>

<p class=MsoNormal style='text-align:justify;text-justify:inter-ideograph;
line-height:150%'><span lang=EN-US style='font-size:14.0pt;line-height:150%;
font-family:"Times New Roman",serif'>In conclusion, diabetic retinopathy is a
serious complication of diabetes that affects the retina and can lead to vision
loss if left untreated. Early detection and timely intervention are crucial in
managing the condition effectively. Regular eye examinations, adherence to
diabetes management strategies, and lifestyle modifications play a pivotal role
in preventing and minimizing the impact of diabetic retinopathy. Close
collaboration between patients, healthcare providers, and eye specialists is
essential to ensure comprehensive care and optimize visual outcomes for
individuals with diabetic retinopathy.<o:p></o:p></span></p>

<span lang=EN-US style='font-size:14.0pt;line-height:107%;font-family:"Times New Roman",serif;
mso-fareast-font-family:"Times New Roman";mso-fareast-theme-font:minor-fareast;
mso-ansi-language:EN-US;mso-fareast-language:EN-US;mso-bidi-language:AR-SA'><br
clear=all style='mso-special-character:line-break;page-break-before:always'>
</span>

<p class=MsoNormal><span lang=EN-US style='font-size:14.0pt;line-height:107%;
font-family:"Times New Roman",serif'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal align=right style='text-align:right;line-height:150%'><b><u><span
lang=EN-US style='font-size:36.0pt;line-height:150%;font-family:"Cambria",serif;
mso-bidi-font-family:"Times New Roman"'>F</span></u></b><b><u><span lang=EN-US
style='font-size:26.0pt;line-height:150%;font-family:"Cambria",serif;
mso-bidi-font-family:"Times New Roman"'>uture Work<o:p></o:p></span></u></b></p>

<p class=MsoNormal><span lang=EN-US style='font-size:16.0pt;line-height:107%;
font-family:"Times New Roman",serif'>In future work for transfer learning in
diabetes risk assessment and retinal biomarker detection, researchers can focus
on exploring advanced deep learning architectures specifically designed for
retinography analysis. Integrating multi-modal data, such as patient
demographics and clinical information, alongside retinal images, can improve
prediction models. <o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-size:16.0pt;line-height:107%;
font-family:"Times New Roman",serif'>The availability of large-scale, diverse
datasets will be crucial for training and evaluating these models, ensuring
generalizability across different populations. Additionally, developing methods
for explaining ability and interpretability of the models' decisions can
enhance trust and acceptance in clinical settings. <o:p></o:p></span></p>

<p class=MsoNormal style='text-indent:36.0pt'><span lang=EN-US
style='font-size:16.0pt;line-height:107%;font-family:"Times New Roman",serif'>The
translation of transfer learning models into real-world clinical practice,
validation studies in diverse patient populations, and assessing their impact
on healthcare outcomes are vital for their practical utility.<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-family:"Segoe UI",sans-serif;
color:#374151;background:#F7F7F8'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-family:"Segoe UI",sans-serif;
color:#374151;background:#F7F7F8'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-family:"Segoe UI",sans-serif;
color:#374151;background:#F7F7F8'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-family:"Segoe UI",sans-serif;
color:#374151;background:#F7F7F8'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-family:"Segoe UI",sans-serif;
color:#374151;background:#F7F7F8'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-family:"Segoe UI",sans-serif;
color:#374151;background:#F7F7F8'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-family:"Segoe UI",sans-serif;
color:#374151;background:#F7F7F8'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-family:"Segoe UI",sans-serif;
color:#374151;background:#F7F7F8'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-family:"Segoe UI",sans-serif;
color:#374151;background:#F7F7F8'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-family:"Segoe UI",sans-serif;
color:#374151;background:#F7F7F8'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-family:"Segoe UI",sans-serif;
color:#374151;background:#F7F7F8'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-family:"Segoe UI",sans-serif;
color:#374151;background:#F7F7F8'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-family:"Segoe UI",sans-serif;
color:#374151;background:#F7F7F8'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-family:"Segoe UI",sans-serif;
color:#374151;background:#F7F7F8'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-family:"Segoe UI",sans-serif;
color:#374151;background:#F7F7F8'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-family:"Segoe UI",sans-serif;
color:#374151;background:#F7F7F8'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:252.0pt;text-indent:36.0pt'><b><span
lang=EN-US style='font-size:28.0pt;line-height:107%;font-family:"Cambria",serif;
mso-bidi-font-family:Aldhabi'>|<span style='mso-spacerun:yes'>  </span><span
style='mso-tab-count:2'>         </span><span style='mso-spacerun:yes'> </span></span></b><b><span
lang=EN-US style='font-size:48.0pt;line-height:107%;font-family:"Cambria",serif;
mso-bidi-font-family:Aldhabi'>R</span></b><b><span lang=EN-US style='font-size:
28.0pt;line-height:107%;font-family:"Cambria",serif;mso-bidi-font-family:Aldhabi'>eferences<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpFirst style='text-align:justify;text-justify:inter-ideograph;
line-height:normal'><b><span lang=EN-US style='font-size:16.0pt;font-family:
"Times New Roman",serif;mso-fareast-font-family:Batang'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify;text-justify:
inter-ideograph;line-height:normal'><b><span lang=EN-US style='font-size:16.0pt;
font-family:"Times New Roman",serif;mso-fareast-font-family:Batang'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify;text-justify:
inter-ideograph;line-height:normal'><b><span lang=EN-US style='font-size:16.0pt;
font-family:"Times New Roman",serif;mso-fareast-font-family:Batang'><o:p>&nbsp;</o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:25.05pt;mso-add-space:
auto;text-align:justify;text-justify:inter-ideograph;text-indent:-18.0pt;
line-height:normal;mso-list:l1 level1 lfo3'><![if !supportLists]><b><span
lang=EN-US style='font-size:20.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:"Times New Roman"'><span style='mso-list:Ignore'>1.<span
style='font:7.0pt "Times New Roman"'>&nbsp; </span></span></span></b><![endif]><span
lang=EN-US style='font-size:16.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:Batang;color:#222222;background:white'><span
style='mso-spacerun:yes'> </span>Department of Computer Engineering, College of
Engineering and Petroleum, Kuwait University, P.O. Box 5969, Safat 13060,
Kuwait</span><b><span lang=EN-US style='font-size:16.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:Batang'><o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify;text-justify:
inter-ideograph;line-height:normal'><em><span lang=EN-US style='font-size:16.0pt;
color:#222222;background:white'>Appl. Sci.</span></em><span lang=EN-US
style='font-size:16.0pt;font-family:"Times New Roman",serif;color:#222222;
background:white'>&nbsp;<b>2023</b>,&nbsp;<em>13</em>(9), 5685;&nbsp;</span><span
lang=EN-US><a href="https://doi.org/10.3390/app13095685"><b><span
style='font-size:16.0pt;font-family:"Times New Roman",serif;background:white'>https://doi.org/10.3390/app13095685</span></b></a></span><b><span
lang=EN-US style='font-size:16.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:Batang'><o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpLast style='margin-left:25.05pt;mso-add-space:
auto;text-align:justify;text-justify:inter-ideograph;text-indent:-18.0pt;
line-height:normal;mso-list:l1 level1 lfo3'><![if !supportLists]><b><span
lang=EN-US style='font-size:20.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:"Times New Roman"'><span style='mso-list:Ignore'>2.<span
style='font:7.0pt "Times New Roman"'>&nbsp; </span></span></span></b><![endif]><span
lang=EN-US><a href="https://arxiv.org/abs/1905.07203"><b><span
style='font-size:16.0pt;font-family:"Times New Roman",serif;mso-fareast-font-family:
Batang'>https://arxiv.org/abs/1905.07203</span></b></a></span><b><span
lang=EN-US style='font-size:16.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:Batang'><o:p></o:p></span></b></p>

<h1 style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
25.05pt;text-indent:-18.0pt;mso-list:l1 level1 lfo3;background:#FCFCFC'><![if !supportLists]><b><span
lang=EN-US style='font-size:20.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:"Times New Roman";color:#333333'><span
style='mso-list:Ignore'>3.<span style='font:7.0pt "Times New Roman"'>&nbsp; </span></span></span></b><![endif]><span
lang=EN-US style='font-size:16.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:Batang;color:#333333'>Comparative Analysis of Different
Models for Diabetic Retinopathy Classification. Lavanya Bagadi, E. Pavankumar,
A. Likitha, K. Niranjan &amp; B. Nani . <b>[</b></span><span lang=EN-US><a
href="https://link.springer.com/chapter/10.1007/978-981-16-8512-5_28"><b><span
style='font-size:16.0pt;font-family:"Times New Roman",serif;mso-fareast-font-family:
Batang'>Reference</span></b></a></span><b><span lang=EN-US style='font-size:
16.0pt;font-family:"Times New Roman",serif;mso-fareast-font-family:Batang;
color:#333333'>]</span></b><span lang=EN-US style='font-size:16.0pt;font-family:
"Times New Roman",serif;mso-fareast-font-family:Batang;color:#333333'><o:p></o:p></span></h1>

<p class=MsoListParagraphCxSpFirst style='margin-left:25.05pt;mso-add-space:
auto;text-align:justify;text-justify:inter-ideograph;text-indent:-18.0pt;
line-height:normal;mso-list:l1 level1 lfo3'><![if !supportLists]><b><span
lang=EN-US style='font-size:20.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:"Times New Roman"'><span style='mso-list:Ignore'>4.<span
style='font:7.0pt "Times New Roman"'>&nbsp; </span></span></span></b><![endif]><span
lang=EN-US style='font-size:16.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:Batang;color:#202124'><span
style='mso-spacerun:yes'> </span>“The effect of model size on accuracy”.</span><span
lang=EN-US style='font-size:16.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:Batang'>Parhaam Honolulu, Hawaii, United States<b> [</b></span><span
lang=EN-US><a
href="https://www.kaggle.com/code/the314arham/the-effect-of-model-size-on-accuracy/notebook#ABSTRACT"><b><span
style='font-size:16.0pt;font-family:"Times New Roman",serif;mso-fareast-font-family:
Batang'>Reference</span></b></a></span><b><span lang=EN-US style='font-size:
16.0pt;font-family:"Times New Roman",serif;mso-fareast-font-family:Batang'>]<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:25.05pt;mso-add-space:
auto;text-align:justify;text-justify:inter-ideograph;text-indent:-18.0pt;
line-height:normal;mso-list:l1 level1 lfo3'><![if !supportLists]><b><span
lang=EN-US style='font-size:20.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:"Times New Roman"'><span style='mso-list:Ignore'>5.<span
style='font:7.0pt "Times New Roman"'>&nbsp; </span></span></span></b><![endif]><span
lang=EN-US style='font-size:16.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:Batang'>DL-Diabetic
RetinopathycDetection-95%Acc-CN.<span style='mso-spacerun:yes'>  </span>Data
Scientist | AI Researcher at freelanceAbadan, Khuzestan Province, Iran </span><span
lang=EN-US><a
href="https://www.kaggle.com/code/parisanahmadi/dl-diabetic-retinopathycdetection-95-acc-cnn#Diabet-Retinopathy-Detection-Section"><b><span
style='font-size:16.0pt;font-family:"Times New Roman",serif;mso-fareast-font-family:
Batang'>[Reference]</span></b></a></span><span lang=EN-US style='font-size:
16.0pt;font-family:"Times New Roman",serif;mso-fareast-font-family:Batang'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:25.05pt;mso-add-space:
auto;text-align:justify;text-justify:inter-ideograph;text-indent:-18.0pt;
line-height:normal;mso-list:l1 level1 lfo3'><![if !supportLists]><b><span
lang=EN-US style='font-size:20.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:"Times New Roman"'><span style='mso-list:Ignore'>6.<span
style='font:7.0pt "Times New Roman"'>&nbsp; </span></span></span></b><![endif]><span
lang=EN-US style='font-size:16.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:Batang'>“Diabetic Retinopathy Detection and
Classification”</span><span lang=EN-US style='font-size:16.0pt;font-family:
"Times New Roman",serif'> </span><span lang=EN-US style='font-size:16.0pt;
font-family:"Times New Roman",serif;mso-fareast-font-family:Batang'>Student at
Birla Institute of Technology Ranchi, Jharkhand, India <b><span
style='color:#0070C0'>[</span></b></span><span lang=EN-US><a
href="https://www.kaggle.com/code/akshat0007/diabetic-retinopathy-detection-and-classification"><b><span
style='font-size:16.0pt;font-family:"Times New Roman",serif;mso-fareast-font-family:
Batang'>https://www.kaggle.com/code/akshat0007/diabetic-retinopathy-detection-and-classification</span></b></a></span><b><span
lang=EN-US style='font-size:16.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:Batang;color:#0070C0'><span style='mso-spacerun:yes'> 
</span>]</span></b><span lang=EN-US style='font-size:16.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:Batang'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:25.05pt;mso-add-space:
auto;text-align:justify;text-justify:inter-ideograph;text-indent:-18.0pt;
line-height:normal;mso-list:l1 level1 lfo3'><![if !supportLists]><span
class=MsoHyperlink><b><span lang=EN-US style='font-size:20.0pt;font-family:
"Times New Roman",serif;mso-fareast-font-family:"Times New Roman";text-decoration:
none;text-underline:none'><span style='mso-list:Ignore'>7.<span
style='font:7.0pt "Times New Roman"'>&nbsp; </span></span></span></b></span><![endif]><span
lang=EN-US style='font-size:16.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:Batang'>“Deep Transfer Learning Models for Medical
Diabetic Detection”</span><span lang=EN-US style='font-size:16.0pt;font-family:
"Times New Roman",serif'> </span><span lang=EN-US style='font-size:16.0pt;
font-family:"Times New Roman",serif;mso-fareast-font-family:Batang'>Nour Eldeen
M. Khalifa, Mohamed Loey, Mohamed Hamed N. Taha, and Hamed Nasr Eldin T.
Mohamed </span><span lang=EN-US><a
href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7085308/"><b><span
style='font-size:16.0pt;font-family:"Times New Roman",serif;mso-fareast-font-family:
Batang'>[https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7085308/]</span></b></a></span><span
class=MsoHyperlink><span lang=EN-US style='font-size:16.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:Batang'><o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:25.05pt;mso-add-space:
auto;text-align:justify;text-justify:inter-ideograph;text-indent:-18.0pt;
line-height:normal;mso-list:l1 level1 lfo3'><![if !supportLists]><span
class=MsoHyperlink><b><span lang=EN-US style='font-size:20.0pt;font-family:
"Times New Roman",serif;mso-fareast-font-family:"Times New Roman";text-decoration:
none;text-underline:none'><span style='mso-list:Ignore'>8.<span
style='font:7.0pt "Times New Roman"'>&nbsp; </span></span></span></b></span><![endif]><span
lang=EN-US style='font-size:16.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:Batang'>Diabetic Retinopathy 224x224 (2019 Data)<span
style='mso-tab-count:3'>                      </span><span style='mso-tab-count:
1'>   </span><span style='mso-spacerun:yes'>             </span>Reference</span><span
lang=EN-US><a
href="https://www.kaggle.com/datasets/sovitrath/diabetic-retinopathy-224x224-2019-data?select=colored_images"><b><span
style='font-size:16.0pt;font-family:"Times New Roman",serif;mso-fareast-font-family:
Batang'>:[https://www.kaggle.com/datasets/sovitrath/diabetic-retinopathy-224x224-2019-data?select=colored_images]</span></b></a></span><span
class=MsoHyperlink><span lang=EN-US style='font-size:16.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:Batang'><o:p></o:p></span></span></p>

<p class=MsoListParagraphCxSpMiddle style='margin-left:25.05pt;mso-add-space:
auto;text-align:justify;text-justify:inter-ideograph;text-indent:-18.0pt;
line-height:normal;mso-list:l1 level1 lfo3'><![if !supportLists]><b><span
lang=EN-US style='font-size:20.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:"Times New Roman"'><span style='mso-list:Ignore'>9.<span
style='font:7.0pt "Times New Roman"'>&nbsp; </span></span></span></b><![endif]><span
lang=EN-US style='font-size:16.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:Batang'>TensorFlow Reference [</span><span lang=EN-US><a
href="https://www.tensorflow.org/guide"><span style='font-size:16.0pt;
font-family:"Times New Roman",serif;mso-fareast-font-family:Batang'>https://www.tensorflow.org/guide</span></a></span><span
lang=EN-US style='font-size:16.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:Batang'>]<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpLast style='margin-left:25.05pt;mso-add-space:
auto;text-align:justify;text-justify:inter-ideograph;text-indent:-18.0pt;
line-height:normal;mso-list:l1 level1 lfo3'><![if !supportLists]><b><span
lang=EN-US style='font-size:20.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:"Times New Roman"'><span style='mso-list:Ignore'>10.<span
style='font:7.0pt "Times New Roman"'>&nbsp; </span></span></span></b><![endif]><span
lang=EN-US style='font-size:16.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:Batang'>Keras Tuner Reference <b>[</b></span><span
lang=EN-US><a href="https://keras.io/api/applications/%5d"><b><span
style='font-size:16.0pt;font-family:"Times New Roman",serif;mso-fareast-font-family:
Batang'>https://keras.io/api/applications/]</span></b></a></span><span
lang=EN-US style='font-size:16.0pt;font-family:"Times New Roman",serif;
mso-fareast-font-family:Batang'><o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;text-justify:inter-ideograph'><span
lang=EN-US style='font-size:16.0pt;line-height:107%;font-family:"Batang",serif;
mso-bidi-font-family:Aldhabi'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraph style='text-align:justify;text-justify:inter-ideograph'><span
lang=EN-US style='font-size:16.0pt;line-height:107%;font-family:"Batang",serif;
mso-bidi-font-family:Aldhabi'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='text-align:justify;text-justify:inter-ideograph'><b><span
lang=EN-US style='font-size:16.0pt;line-height:107%;font-family:"Batang",serif;
mso-bidi-font-family:Aldhabi'><o:p>&nbsp;</o:p></span></b></p>

<!--EndFragment-->
</body>

</html>
