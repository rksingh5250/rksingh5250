- 👋 Hi, I’m @rksingh5250
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
rksingh5250/rksingh5250 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

<?xml version='1.0' encoding='utf-8' ?>

<!-- build 20203.20.0918.1727                               -->
<workbook source-build='2020.3.1 (20203.20.0918.1727)' source-platform='win' version='18.1' xmlns:user='http://www.tableausoftware.com/xml/user'>
  <document-format-change-manifest>
    <AutoCreateAndUpdateDSDPhoneLayouts />
    <IntuitiveSorting />
    <IntuitiveSorting_SP2 />
    <MapboxVectorStylesAndLayers />
    <_.fcp.MarkAnimation.true...MarkAnimation />
    <_.fcp.ObjectModelEncapsulateLegacy.true...ObjectModelEncapsulateLegacy />
    <_.fcp.ObjectModelTableType.true...ObjectModelTableType />
    <_.fcp.SchemaViewerObjectModel.true...SchemaViewerObjectModel />
    <_.fcp.SetMembershipControl.true...SetMembershipControl />
    <SheetIdentifierTracking />
    <WindowsPersistSimpleIdentifiers />
    <WorksheetBackgroundTransparency />
    <ZoneBackgroundTransparency />
  </document-format-change-manifest>
  <preferences>
    <preference name='ui.encoding.shelf.height' value='24' />
    <preference name='ui.shelf.height' value='26' />
  </preferences>
  <style>
    <_.fcp.MarkAnimation.true...style-rule element='animation'>
      <format attr='animation-on' value='ao-on' />
      <format attr='animation-duration' value='10' />
    </_.fcp.MarkAnimation.true...style-rule>
  </style>
  <datasources>
    <datasource caption='Sheet2 (Task-6_Dataset)' inline='true' name='federated.0bd2dna07rjett15ohm5x19xsxxb' version='18.1'>
      <connection class='federated'>
        <named-connections>
          <named-connection caption='Task-6_Dataset' name='excel-direct.14ryfll0buhcxs13jmz1l12qdsv5'>
            <connection class='excel-direct' cleaning='no' compat='no' dataRefreshTime='' filename='Z:/GithubProjects/The-Sparks-Foundation-Tasks/Task-6_Dataset.xlsx' interpretationMode='0' password='' server='' validate='no' />
          </named-connection>
        </named-connections>
        <_.fcp.ObjectModelEncapsulateLegacy.false...relation connection='excel-direct.14ryfll0buhcxs13jmz1l12qdsv5' name='Covid19' table='[Covid19$]' type='table'>
          <columns gridOrigin='A1:I7089:no:A1:I7089:0' header='yes' outcome='6'>
            <column datatype='integer' name='Sno' ordinal='0' />
            <column datatype='date' name='Date' ordinal='1' />
            <column datatype='datetime' name='Time' ordinal='2' />
            <column datatype='string' name='State/UnionTerritory' ordinal='3' />
            <column datatype='integer' name='ConfirmedIndianNational' ordinal='4' />
            <column datatype='integer' name='ConfirmedForeignNational' ordinal='5' />
            <column datatype='integer' name='Cured' ordinal='6' />
            <column datatype='integer' name='Deaths' ordinal='7' />
            <column datatype='integer' name='Confirmed' ordinal='8' />
          </columns>
        </_.fcp.ObjectModelEncapsulateLegacy.false...relation>
        <_.fcp.ObjectModelEncapsulateLegacy.true...relation connection='excel-direct.14ryfll0buhcxs13jmz1l12qdsv5' name='Covid19' table='[Covid19$]' type='table'>
          <columns gridOrigin='A1:I7089:no:A1:I7089:0' header='yes' outcome='6'>
            <column datatype='integer' name='Sno' ordinal='0' />
            <column datatype='date' name='Date' ordinal='1' />
            <column datatype='datetime' name='Time' ordinal='2' />
            <column datatype='string' name='State/UnionTerritory' ordinal='3' />
            <column datatype='integer' name='ConfirmedIndianNational' ordinal='4' />
            <column datatype='integer' name='ConfirmedForeignNational' ordinal='5' />
            <column datatype='integer' name='Cured' ordinal='6' />
            <column datatype='integer' name='Deaths' ordinal='7' />
            <column datatype='integer' name='Confirmed' ordinal='8' />
          </columns>
        </_.fcp.ObjectModelEncapsulateLegacy.true...relation>
        <metadata-records>
          <metadata-record class='capability'>
            <remote-name />
            <remote-type>0</remote-type>
            <parent-name>[Covid19]</parent-name>
            <remote-alias />
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='context'>0</attribute>
              <attribute datatype='string' name='gridOrigin'>&quot;A1:I7089:no:A1:I7089:0&quot;</attribute>
              <attribute datatype='boolean' name='header'>true</attribute>
              <attribute datatype='integer' name='outcome'>6</attribute>
            </attributes>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Sno</remote-name>
            <remote-type>20</remote-type>
            <local-name>[Sno]</local-name>
            <parent-name>[Covid19]</parent-name>
            <remote-alias>Sno</remote-alias>
            <ordinal>0</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[Covid19_5E61D0F462BC4F2281CC7002DE1DA561]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Date</remote-name>
            <remote-type>7</remote-type>
            <local-name>[Date]</local-name>
            <parent-name>[Covid19]</parent-name>
            <remote-alias>Date</remote-alias>
            <ordinal>1</ordinal>
            <local-type>date</local-type>
            <aggregation>Year</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;DATE&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[Covid19_5E61D0F462BC4F2281CC7002DE1DA561]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Time</remote-name>
            <remote-type>7</remote-type>
            <local-name>[Time]</local-name>
            <parent-name>[Covid19]</parent-name>
            <remote-alias>Time</remote-alias>
            <ordinal>2</ordinal>
            <local-type>datetime</local-type>
            <aggregation>Year</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;DATE&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[Covid19_5E61D0F462BC4F2281CC7002DE1DA561]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>State/UnionTerritory</remote-name>
            <remote-type>130</remote-type>
            <local-name>[State/UnionTerritory]</local-name>
            <parent-name>[Covid19]</parent-name>
            <remote-alias>State/UnionTerritory</remote-alias>
            <ordinal>3</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='1' name='LEN_RIN_S2' />
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;WSTR&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[Covid19_5E61D0F462BC4F2281CC7002DE1DA561]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>ConfirmedIndianNational</remote-name>
            <remote-type>20</remote-type>
            <local-name>[ConfirmedIndianNational]</local-name>
            <parent-name>[Covid19]</parent-name>
            <remote-alias>ConfirmedIndianNational</remote-alias>
            <ordinal>4</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[Covid19_5E61D0F462BC4F2281CC7002DE1DA561]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>ConfirmedForeignNational</remote-name>
            <remote-type>20</remote-type>
            <local-name>[ConfirmedForeignNational]</local-name>
            <parent-name>[Covid19]</parent-name>
            <remote-alias>ConfirmedForeignNational</remote-alias>
            <ordinal>5</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[Covid19_5E61D0F462BC4F2281CC7002DE1DA561]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Cured</remote-name>
            <remote-type>20</remote-type>
            <local-name>[Cured]</local-name>
            <parent-name>[Covid19]</parent-name>
            <remote-alias>Cured</remote-alias>
            <ordinal>6</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[Covid19_5E61D0F462BC4F2281CC7002DE1DA561]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Deaths</remote-name>
            <remote-type>20</remote-type>
            <local-name>[Deaths]</local-name>
            <parent-name>[Covid19]</parent-name>
            <remote-alias>Deaths</remote-alias>
            <ordinal>7</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[Covid19_5E61D0F462BC4F2281CC7002DE1DA561]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Confirmed</remote-name>
            <remote-type>20</remote-type>
            <local-name>[Confirmed]</local-name>
            <parent-name>[Covid19]</parent-name>
            <remote-alias>Confirmed</remote-alias>
            <ordinal>8</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='DebugRemoteType'>&quot;I8&quot;</attribute>
            </attributes>
            <_.fcp.ObjectModelEncapsulateLegacy.true...object-id>[Covid19_5E61D0F462BC4F2281CC7002DE1DA561]</_.fcp.ObjectModelEncapsulateLegacy.true...object-id>
          </metadata-record>
        </metadata-records>
      </connection>
      <aliases enabled='yes' />
      <column caption='Rank' datatype='integer' name='[Calculation_820218120432779264]' role='measure' type='quantitative'>
        <calculation class='tableau' formula='RANK_UNIQUE(SUM([Confirmed]))'>
          <table-calc ordering-type='Rows' />
        </calculation>
      </column>
      <column caption='Total Cases' datatype='integer' name='[Calculation_820218120473554946]' role='measure' type='quantitative'>
        <calculation class='tableau' formula='MAX([Confirmed])' />
      </column>
      <column caption='Confirmed Foreign National' datatype='integer' hidden='true' name='[ConfirmedForeignNational]' role='measure' type='quantitative' />
      <column caption='Confirmed Indian National' datatype='integer' hidden='true' name='[ConfirmedIndianNational]' role='measure' type='quantitative' />
      <column datatype='date' name='[Date]' role='dimension' type='ordinal' />
      <column caption='State/UnionTerritory1' datatype='string' name='[State/UnionTerritory]' role='dimension' semantic-role='[State].[Name]' type='nominal'>
        <semantic-values semantic-role='[State].[Name]'>
          <semantic-value key='&quot;Dadra and Nagar Haveli and Daman and Diu&quot;' value='&quot;Dadra and Nagar Haveli&quot;' />
        </semantic-values>
      </column>
      <_.fcp.ObjectModelTableType.true...column caption='Covid19' datatype='table' name='[__tableau_internal_object_id__].[Covid19_5E61D0F462BC4F2281CC7002DE1DA561]' role='measure' type='quantitative' />
      <column-instance column='[Date]' derivation='MDY' name='[md:Date:ok]' pivot='key' type='ordinal' />
      <column-instance column='[State/UnionTerritory]' derivation='None' name='[none:State/UnionTerritory:nk]' pivot='key' type='nominal' />
      <group caption='Action (MDY(Date))' hidden='true' name='[Action (MDY(Date))]' name-style='unqualified' user:auto-column='sheet_link'>
        <groupfilter function='crossjoin'>
          <groupfilter function='level-members' level='[md:Date:ok]' />
        </groupfilter>
      </group>
      <group hidden='true' name='[Exclusions (MDY(Date),State/UnionTerritory1)]' name-style='unqualified' user:auto-column='exclude'>
        <groupfilter function='crossjoin'>
          <groupfilter function='level-members' level='[md:Date:ok]' />
          <groupfilter function='level-members' level='[none:State/UnionTerritory:nk]' />
        </groupfilter>
      </group>
      <layout _.fcp.SchemaViewerObjectModel.false...dim-percentage='0.5' _.fcp.SchemaViewerObjectModel.false...measure-percentage='0.4' dim-ordering='alphabetic' measure-ordering='alphabetic' show-structure='true' />
      <semantic-values>
        <semantic-value key='[Country].[Name]' value='&quot;India&quot;' />
      </semantic-values>
      <_.fcp.ObjectModelEncapsulateLegacy.true...object-graph>
        <objects>
          <object caption='Covid19' id='Covid19_5E61D0F462BC4F2281CC7002DE1DA561'>
            <properties context=''>
              <relation connection='excel-direct.14ryfll0buhcxs13jmz1l12qdsv5' name='Covid19' table='[Covid19$]' type='table'>
                <columns gridOrigin='A1:I7089:no:A1:I7089:0' header='yes' outcome='6'>
                  <column datatype='integer' name='Sno' ordinal='0' />
                  <column datatype='date' name='Date' ordinal='1' />
                  <column datatype='datetime' name='Time' ordinal='2' />
                  <column datatype='string' name='State/UnionTerritory' ordinal='3' />
                  <column datatype='integer' name='ConfirmedIndianNational' ordinal='4' />
                  <column datatype='integer' name='ConfirmedForeignNational' ordinal='5' />
                  <column datatype='integer' name='Cured' ordinal='6' />
                  <column datatype='integer' name='Deaths' ordinal='7' />
                  <column datatype='integer' name='Confirmed' ordinal='8' />
                </columns>
              </relation>
            </properties>
          </object>
        </objects>
      </_.fcp.ObjectModelEncapsulateLegacy.true...object-graph>
    </datasource>
  </datasources>
  <mapsources>
    <mapsource name='Tableau' />
  </mapsources>
  <actions>
    <action caption='Highlight 1 (generated)' name='[Action1]'>
      <activation auto-clear='true' type='on-select' />
      <source dashboard='Dashboard ' type='sheet' />
      <command command='tsc:brush'>
        <param name='special-fields' value='date-time' />
        <param name='target' value='Dashboard ' />
      </command>
    </action>
  </actions>
  <worksheets>
    <worksheet name='Cure vs Death plot'>
      <layout-options>
        <title>
          <formatted-text />
        </title>
      </layout-options>
      <table>
        <view>
          <datasources>
            <datasource caption='Sheet2 (Task-6_Dataset)' name='federated.0bd2dna07rjett15ohm5x19xsxxb' />
          </datasources>
          <mapsources>
            <mapsource name='Tableau' />
          </mapsources>
          <datasource-dependencies datasource='federated.0bd2dna07rjett15ohm5x19xsxxb'>
            <column datatype='integer' name='[Confirmed]' role='measure' type='quantitative' />
            <column datatype='integer' name='[Cured]' role='measure' type='quantitative' />
            <column datatype='date' name='[Date]' role='dimension' type='ordinal' />
            <column datatype='integer' name='[Deaths]' role='measure' type='quantitative' />
            <column caption='State/UnionTerritory1' datatype='string' name='[State/UnionTerritory]' role='dimension' semantic-role='[State].[Name]' type='nominal'>
              <semantic-values semantic-role='[State].[Name]'>
                <semantic-value key='&quot;Dadra and Nagar Haveli and Daman and Diu&quot;' value='&quot;Dadra and Nagar Haveli&quot;' />
              </semantic-values>
            </column>
            <column-instance column='[Cured]' derivation='Max' name='[max:Cured:qk]' pivot='key' type='quantitative' />
            <column-instance column='[Deaths]' derivation='Max' name='[max:Deaths:qk]' pivot='key' type='quantitative' />
            <column-instance column='[Date]' derivation='MDY' name='[md:Date:ok]' pivot='key' type='ordinal' />
            <column-instance column='[State/UnionTerritory]' derivation='None' name='[none:State/UnionTerritory:nk]' pivot='key' type='nominal' />
            <column-instance column='[Confirmed]' derivation='Sum' name='[sum:Confirmed:qk]' pivot='key' type='quantitative' />
          </datasource-dependencies>
          <filter class='categorical' column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[none:State/UnionTerritory:nk]'>
            <groupfilter function='except' user:ui-domain='relevant' user:ui-enumeration='exclusive' user:ui-marker='enumerate'>
              <groupfilter function='level-members' level='[none:State/UnionTerritory:nk]' />
              <groupfilter function='union'>
                <groupfilter function='member' level='[none:State/UnionTerritory:nk]' member='&quot;Dadar Nagar Haveli&quot;' />
                <groupfilter function='member' level='[none:State/UnionTerritory:nk]' member='&quot;Daman &amp; Diu&quot;' />
                <groupfilter function='member' level='[none:State/UnionTerritory:nk]' member='&quot;Nagaland\#&quot;' />
                <groupfilter function='member' level='[none:State/UnionTerritory:nk]' member='&quot;Tamil Nadu&quot;' />
                <groupfilter function='member' level='[none:State/UnionTerritory:nk]' member='&quot;Telangana&quot;' />
                <groupfilter function='member' level='[none:State/UnionTerritory:nk]' member='&quot;Telangana***&quot;' />
                <groupfilter function='member' level='[none:State/UnionTerritory:nk]' member='&quot;Telengana***&quot;' />
                <groupfilter function='member' level='[none:State/UnionTerritory:nk]' member='&quot;Unassigned&quot;' />
              </groupfilter>
            </groupfilter>
          </filter>
          <filter class='categorical' column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[none:State/UnionTerritory:nk]' kind='hide'>
            <groupfilter function='except' user:ui-domain='relevant' user:ui-enumeration='exclusive' user:ui-manual-selection='true' user:ui-manual-selection-all-when-empty='true' user:ui-marker='enumerate'>
              <groupfilter function='level-members' level='[none:State/UnionTerritory:nk]' />
              <groupfilter function='member' level='[none:State/UnionTerritory:nk]' member='&quot;Cases being reassigned to states&quot;' />
            </groupfilter>
          </filter>
          <shelf-sorts>
            <shelf-sort-v2 dimension-to-sort='[federated.0bd2dna07rjett15ohm5x19xsxxb].[none:State/UnionTerritory:nk]' direction='DESC' is-on-innermost-dimension='true' measure-to-sort-by='[federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Cured:qk]' shelf='columns' />
          </shelf-sorts>
          <slices>
            <column>[federated.0bd2dna07rjett15ohm5x19xsxxb].[none:State/UnionTerritory:nk]</column>
          </slices>
          <aggregation value='true' />
        </view>
        <style>
          <style-rule element='axis'>
            <format attr='stroke-size' scope='cols' value='2' />
            <encoding attr='space' class='0' field='[federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Cured:qk]' field-type='quantitative' range-type='uniform' scale='log' scope='rows' type='space' />
            <format attr='title' class='0' field='[federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Cured:qk]' scope='rows' value=' Cured' />
            <encoding attr='space' class='0' field='[federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Deaths:qk]' field-type='quantitative' scale='log' scope='rows' type='space' />
            <format attr='title' class='0' field='[federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Deaths:qk]' scope='rows' value='Deaths' />
            <format attr='width' field='[federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Cured:qk]' value='120' />
            <format attr='width' field='[federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Deaths:qk]' value='120' />
          </style-rule>
          <style-rule element='header'>
            <format attr='border-style' data-class='total' scope='cols' value='dashed' />
          </style-rule>
          <style-rule element='mark'>
            <encoding attr='color' field='[federated.0bd2dna07rjett15ohm5x19xsxxb].[sum:Confirmed:qk]' palette='tableau-map-temperatur' type='interpolated' />
          </style-rule>
          <style-rule element='pane'>
            <format attr='border-style' data-class='total' scope='cols' value='dotted' />
          </style-rule>
          <style-rule element='table'>
            <format attr='background-color' value='#000000' />
            <format attr='omit-on-special' field='[federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Deaths:qk]' value='false' />
            <format attr='break-on-special' field='[federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Deaths:qk]' value='false' />
            <format attr='show-null-value-warning' field='[federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Deaths:qk]' value='false' />
            <format attr='omit-on-special' field='[federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Cured:qk]' value='false' />
            <format attr='break-on-special' field='[federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Cured:qk]' value='false' />
            <format attr='show-null-value-warning' field='[federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Cured:qk]' value='false' />
          </style-rule>
          <style-rule element='worksheet'>
            <format attr='display-field-labels' scope='rows' value='false' />
            <format attr='color' value='#ffffff' />
            <format attr='display-field-labels' scope='cols' value='false' />
          </style-rule>
          <style-rule element='refline'>
            <format attr='line-visibility' scope='cols' value='on' />
            <format attr='line-pattern-only' scope='cols' value='dotted' />
          </style-rule>
          <style-rule element='gridline'>
            <format attr='stroke-size' scope='cols' value='0' />
            <format attr='line-visibility' scope='cols' value='off' />
          </style-rule>
          <style-rule element='zeroline'>
            <format attr='stroke-size' scope='cols' value='0' />
            <format attr='line-visibility' scope='cols' value='off' />
          </style-rule>
          <style-rule element='title'>
            <format attr='color' value='#f5f5f5' />
          </style-rule>
          <style-rule element='map'>
            <format attr='washout' value='0.0' />
          </style-rule>
          <_.fcp.MarkAnimation.true...style-rule element='animation'>
            <format attr='animation-duration' value='0.0010000000474974513' />
            <format attr='animation-style' value='as-synced' />
          </_.fcp.MarkAnimation.true...style-rule>
        </style>
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Bar' />
            <encodings>
              <color column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[sum:Confirmed:qk]' />
              <lod column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[none:State/UnionTerritory:nk]' />
            </encodings>
            <style>
              <style-rule element='mark'>
                <format attr='mark-transparency' value='255' />
                <format attr='mark-labels-show' value='false' />
                <format attr='mark-labels-cull' value='false' />
              </style-rule>
            </style>
          </pane>
          <pane id='1' selection-relaxation-option='selection-relaxation-allow' y-axis-name='[federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Cured:qk]'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Bar' />
            <mark-sizing mark-sizing-setting='marks-scaling-off' />
            <encodings>
              <color column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[sum:Confirmed:qk]' />
              <lod column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[none:State/UnionTerritory:nk]' />
            </encodings>
            <style>
              <style-rule element='mark'>
                <format attr='mark-transparency' value='255' />
                <format attr='size' value='1' />
                <format attr='mark-labels-show' value='false' />
                <format attr='mark-labels-cull' value='false' />
              </style-rule>
            </style>
          </pane>
          <pane id='2' selection-relaxation-option='selection-relaxation-allow' y-axis-name='[federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Deaths:qk]'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Bar' />
            <mark-sizing mark-sizing-setting='marks-scaling-off' />
            <encodings>
              <color column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[sum:Confirmed:qk]' />
              <lod column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[none:State/UnionTerritory:nk]' />
            </encodings>
            <style>
              <style-rule element='mark'>
                <format attr='mark-transparency' value='255' />
                <format attr='size' value='1' />
                <format attr='mark-labels-show' value='false' />
                <format attr='mark-labels-cull' value='false' />
              </style-rule>
            </style>
          </pane>
        </panes>
        <rows>([federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Cured:qk] + [federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Deaths:qk])</rows>
        <cols>[federated.0bd2dna07rjett15ohm5x19xsxxb].[none:State/UnionTerritory:nk]</cols>
        <pages>
          <column>[federated.0bd2dna07rjett15ohm5x19xsxxb].[md:Date:ok]</column>
        </pages>
      </table>
      <simple-id uuid='{D5D31FD3-C2F6-46D6-845D-3899376B548C}' />
    </worksheet>
    <worksheet name='Cured'>
      <layout-options>
        <title>
          <formatted-text />
        </title>
      </layout-options>
      <table>
        <view>
          <datasources>
            <datasource caption='Sheet2 (Task-6_Dataset)' name='federated.0bd2dna07rjett15ohm5x19xsxxb' />
          </datasources>
          <mapsources>
            <mapsource name='Tableau' />
          </mapsources>
          <datasource-dependencies datasource='federated.0bd2dna07rjett15ohm5x19xsxxb'>
            <column datatype='integer' name='[Confirmed]' role='measure' type='quantitative' />
            <column datatype='integer' name='[Cured]' role='measure' type='quantitative' />
            <column datatype='date' name='[Date]' role='dimension' type='ordinal' />
            <column-instance column='[Cured]' derivation='Sum' name='[diff:sum:Cured:ok]' pivot='key' type='ordinal'>
              <table-calc diff-options='Relative' ordering-type='Rows' type='Difference'>
                <address>
                  <value>-1</value>
                </address>
              </table-calc>
            </column-instance>
            <column-instance column='[Date]' derivation='MDY' name='[md:Date:ok]' pivot='key' type='ordinal' />
            <column-instance column='[Confirmed]' derivation='Sum' name='[sum:Confirmed:qk]' pivot='key' type='quantitative' />
            <column-instance column='[Cured]' derivation='Sum' name='[sum:Cured:qk]' pivot='key' type='quantitative' />
          </datasource-dependencies>
          <filter class='categorical' column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[diff:sum:Cured:ok]'>
            <groupfilter function='level-members' level='[diff:sum:Cured:ok]' />
          </filter>
          <slices>
            <column>[federated.0bd2dna07rjett15ohm5x19xsxxb].[diff:sum:Cured:ok]</column>
          </slices>
          <aggregation value='true' />
        </view>
        <style>
          <style-rule element='axis'>
            <format attr='stroke-size' scope='cols' value='2' />
          </style-rule>
          <style-rule element='header'>
            <format attr='border-style' data-class='total' scope='cols' value='dashed' />
          </style-rule>
          <style-rule element='pane'>
            <format attr='border-style' data-class='total' scope='cols' value='dotted' />
          </style-rule>
          <style-rule element='table'>
            <format attr='background-color' value='#000000' />
          </style-rule>
          <style-rule element='worksheet'>
            <format attr='display-field-labels' scope='rows' value='false' />
            <format attr='color' value='#ffffff' />
          </style-rule>
          <style-rule element='refline'>
            <format attr='line-visibility' scope='cols' value='on' />
            <format attr='line-pattern-only' scope='cols' value='dotted' />
          </style-rule>
          <style-rule element='gridline'>
            <format attr='stroke-size' scope='cols' value='0' />
            <format attr='line-visibility' scope='cols' value='off' />
          </style-rule>
          <style-rule element='zeroline'>
            <format attr='stroke-size' scope='cols' value='0' />
            <format attr='line-visibility' scope='cols' value='off' />
          </style-rule>
          <style-rule element='title'>
            <format attr='color' value='#f5f5f5' />
          </style-rule>
          <style-rule element='map'>
            <format attr='washout' value='0.0' />
          </style-rule>
          <_.fcp.MarkAnimation.true...style-rule element='animation'>
            <format attr='animation-duration' value='0.0010000000474974513' />
            <format attr='animation-style' value='as-synced' />
          </_.fcp.MarkAnimation.true...style-rule>
        </style>
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Pie' />
            <mark-sizing mark-sizing-setting='marks-scaling-off' />
            <encodings>
              <text column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[sum:Cured:qk]' />
            </encodings>
            <style>
              <style-rule element='mark'>
                <format attr='mark-labels-cull' value='true' />
                <format attr='mark-labels-line-first' value='true' />
                <format attr='mark-labels-line-last' value='true' />
                <format attr='mark-labels-range-min' value='true' />
                <format attr='mark-labels-range-max' value='true' />
                <format attr='mark-labels-mode' value='all' />
                <format attr='mark-labels-range-scope' value='pane' />
                <format attr='mark-labels-range-field' value='' />
                <format attr='size' value='0.0099999997764825821' />
                <format attr='mark-labels-show' value='true' />
              </style-rule>
            </style>
          </pane>
        </panes>
        <rows />
        <cols />
        <pages>
          <column>[federated.0bd2dna07rjett15ohm5x19xsxxb].[md:Date:ok]</column>
        </pages>
        <mark-labels>
          <mark-label id='0'>
            <tuple-reference>
              <tuple-descriptor>
                <pane-descriptor>
                  <x-fields />
                  <y-fields />
                </pane-descriptor>
                <columns>
                  <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[md:Date:ok]</field>
                  <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[sum:Confirmed:qk]</field>
                </columns>
              </tuple-descriptor>
              <tuple>
                <value>20201007</value>
                <value>6757131</value>
              </tuple>
            </tuple-reference>
            <label-position x='36' y='30' />
          </mark-label>
        </mark-labels>
      </table>
      <simple-id uuid='{1159D8FC-BCDE-4CED-966C-52A4E24DF5FE}' />
    </worksheet>
    <worksheet name='Deceased'>
      <layout-options>
        <title>
          <formatted-text />
        </title>
      </layout-options>
      <table>
        <view>
          <datasources>
            <datasource caption='Sheet2 (Task-6_Dataset)' name='federated.0bd2dna07rjett15ohm5x19xsxxb' />
          </datasources>
          <mapsources>
            <mapsource name='Tableau' />
          </mapsources>
          <datasource-dependencies datasource='federated.0bd2dna07rjett15ohm5x19xsxxb'>
            <column datatype='integer' name='[Confirmed]' role='measure' type='quantitative' />
            <column datatype='integer' name='[Cured]' role='measure' type='quantitative' />
            <column datatype='date' name='[Date]' role='dimension' type='ordinal' />
            <column datatype='integer' name='[Deaths]' role='measure' type='quantitative' />
            <column-instance column='[Cured]' derivation='Sum' name='[diff:sum:Cured:ok]' pivot='key' type='ordinal'>
              <table-calc diff-options='Relative' ordering-type='Rows' type='Difference'>
                <address>
                  <value>-1</value>
                </address>
              </table-calc>
            </column-instance>
            <column-instance column='[Date]' derivation='MDY' name='[md:Date:ok]' pivot='key' type='ordinal' />
            <column-instance column='[Confirmed]' derivation='Sum' name='[sum:Confirmed:qk]' pivot='key' type='quantitative' />
            <column-instance column='[Deaths]' derivation='Sum' name='[sum:Deaths:qk]' pivot='key' type='quantitative' />
          </datasource-dependencies>
          <filter class='categorical' column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[diff:sum:Cured:ok]'>
            <groupfilter function='level-members' level='[diff:sum:Cured:ok]' />
          </filter>
          <slices>
            <column>[federated.0bd2dna07rjett15ohm5x19xsxxb].[diff:sum:Cured:ok]</column>
          </slices>
          <aggregation value='true' />
        </view>
        <style>
          <style-rule element='axis'>
            <format attr='stroke-size' scope='cols' value='2' />
          </style-rule>
          <style-rule element='header'>
            <format attr='border-style' data-class='total' scope='cols' value='dashed' />
          </style-rule>
          <style-rule element='pane'>
            <format attr='border-style' data-class='total' scope='cols' value='dotted' />
          </style-rule>
          <style-rule element='table'>
            <format attr='background-color' value='#000000' />
          </style-rule>
          <style-rule element='worksheet'>
            <format attr='display-field-labels' scope='rows' value='false' />
            <format attr='color' value='#ffffff' />
          </style-rule>
          <style-rule element='refline'>
            <format attr='line-visibility' scope='cols' value='on' />
            <format attr='line-pattern-only' scope='cols' value='dotted' />
          </style-rule>
          <style-rule element='gridline'>
            <format attr='stroke-size' scope='cols' value='0' />
            <format attr='line-visibility' scope='cols' value='off' />
          </style-rule>
          <style-rule element='zeroline'>
            <format attr='stroke-size' scope='cols' value='0' />
            <format attr='line-visibility' scope='cols' value='off' />
          </style-rule>
          <style-rule element='title'>
            <format attr='color' value='#f5f5f5' />
          </style-rule>
          <style-rule element='map'>
            <format attr='washout' value='0.0' />
          </style-rule>
          <_.fcp.MarkAnimation.true...style-rule element='animation'>
            <format attr='animation-duration' value='0.0010000000474974513' />
            <format attr='animation-style' value='as-synced' />
          </_.fcp.MarkAnimation.true...style-rule>
        </style>
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Pie' />
            <mark-sizing mark-sizing-setting='marks-scaling-off' />
            <encodings>
              <text column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[sum:Deaths:qk]' />
            </encodings>
            <style>
              <style-rule element='mark'>
                <format attr='mark-labels-cull' value='true' />
                <format attr='mark-labels-line-first' value='true' />
                <format attr='mark-labels-line-last' value='true' />
                <format attr='mark-labels-range-min' value='true' />
                <format attr='mark-labels-range-max' value='true' />
                <format attr='mark-labels-mode' value='all' />
                <format attr='mark-labels-range-scope' value='pane' />
                <format attr='mark-labels-range-field' value='' />
                <format attr='size' value='0.0099999997764825821' />
                <format attr='mark-labels-show' value='true' />
              </style-rule>
            </style>
          </pane>
        </panes>
        <rows />
        <cols />
        <pages>
          <column>[federated.0bd2dna07rjett15ohm5x19xsxxb].[md:Date:ok]</column>
        </pages>
        <mark-labels>
          <mark-label id='0'>
            <tuple-reference>
              <tuple-descriptor>
                <pane-descriptor>
                  <x-fields />
                  <y-fields />
                </pane-descriptor>
                <columns>
                  <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[md:Date:ok]</field>
                  <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[sum:Confirmed:qk]</field>
                </columns>
              </tuple-descriptor>
              <tuple>
                <value>20201007</value>
                <value>6757131</value>
              </tuple>
            </tuple-reference>
            <label-position x='36' y='30' />
          </mark-label>
        </mark-labels>
      </table>
      <simple-id uuid='{31E7E334-F3E9-4DA9-8C03-B7F8160AD1EC}' />
    </worksheet>
    <worksheet name='Map cases'>
      <layout-options>
        <title>
          <formatted-text>
            <run fontsize='9'> &lt;Page Name&gt;</run>
          </formatted-text>
        </title>
      </layout-options>
      <table>
        <view>
          <datasources>
            <datasource caption='Sheet2 (Task-6_Dataset)' name='federated.0bd2dna07rjett15ohm5x19xsxxb' />
          </datasources>
          <mapsources>
            <mapsource name='Tableau' />
          </mapsources>
          <datasource-dependencies datasource='federated.0bd2dna07rjett15ohm5x19xsxxb'>
            <column datatype='integer' name='[Confirmed]' role='measure' type='quantitative' />
            <column datatype='date' name='[Date]' role='dimension' type='ordinal' />
            <column caption='State/UnionTerritory1' datatype='string' name='[State/UnionTerritory]' role='dimension' semantic-role='[State].[Name]' type='nominal'>
              <semantic-values semantic-role='[State].[Name]'>
                <semantic-value key='&quot;Dadra and Nagar Haveli and Daman and Diu&quot;' value='&quot;Dadra and Nagar Haveli&quot;' />
              </semantic-values>
            </column>
            <column-instance column='[Date]' derivation='MDY' name='[md:Date:ok]' pivot='key' type='ordinal' />
            <column-instance column='[State/UnionTerritory]' derivation='None' name='[none:State/UnionTerritory:nk]' pivot='key' type='nominal' />
            <column-instance column='[Confirmed]' derivation='Sum' name='[rank:sum:Confirmed:qk]' pivot='key' type='quantitative'>
              <table-calc ordering-field='[federated.0bd2dna07rjett15ohm5x19xsxxb].[State/UnionTerritory]' ordering-type='Field' rank-options='Competition,Descending' type='Rank' />
            </column-instance>
          </datasource-dependencies>
          <filter class='quantitative' column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[Latitude (generated)]' included-values='non-null' />
          <filter class='quantitative' column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[Longitude (generated)]' included-values='non-null' />
          <filter class='categorical' column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[none:State/UnionTerritory:nk]'>
            <groupfilter function='except' user:ui-domain='relevant' user:ui-enumeration='exclusive' user:ui-marker='enumerate'>
              <groupfilter function='level-members' level='[none:State/UnionTerritory:nk]' />
              <groupfilter function='union'>
                <groupfilter function='member' level='[none:State/UnionTerritory:nk]' member='&quot;Dadar Nagar Haveli&quot;' />
                <groupfilter function='member' level='[none:State/UnionTerritory:nk]' member='&quot;Daman &amp; Diu&quot;' />
              </groupfilter>
            </groupfilter>
          </filter>
          <slices>
            <column>[federated.0bd2dna07rjett15ohm5x19xsxxb].[none:State/UnionTerritory:nk]</column>
            <column>[federated.0bd2dna07rjett15ohm5x19xsxxb].[Latitude (generated)]</column>
            <column>[federated.0bd2dna07rjett15ohm5x19xsxxb].[Longitude (generated)]</column>
          </slices>
          <aggregation value='true' />
        </view>
        <style>
          <style-rule element='axis'>
            <format attr='stroke-size' scope='cols' value='2' />
          </style-rule>
          <style-rule element='header'>
            <format attr='border-style' data-class='total' scope='cols' value='dashed' />
          </style-rule>
          <style-rule element='mark'>
            <encoding attr='color' field='[federated.0bd2dna07rjett15ohm5x19xsxxb].[rank:sum:Confirmed:qk]' palette='red_green_diverging_10_0' symmetric='false' type='interpolated' />
          </style-rule>
          <style-rule element='pane'>
            <format attr='border-style' data-class='total' scope='cols' value='dotted' />
          </style-rule>
          <style-rule element='table'>
            <format attr='background-color' value='#000000' />
            <format attr='omit-on-special' field='[federated.0bd2dna07rjett15ohm5x19xsxxb].[none:State/UnionTerritory:nk]' value='false' />
            <format attr='break-on-special' field='[federated.0bd2dna07rjett15ohm5x19xsxxb].[none:State/UnionTerritory:nk]' value='false' />
            <format attr='show-null-value-warning' field='[federated.0bd2dna07rjett15ohm5x19xsxxb].[none:State/UnionTerritory:nk]' value='false' />
          </style-rule>
          <style-rule element='worksheet'>
            <format attr='display-field-labels' scope='rows' value='false' />
            <format attr='color' value='#ffffff' />
          </style-rule>
          <style-rule element='refline'>
            <format attr='line-visibility' scope='cols' value='on' />
            <format attr='line-pattern-only' scope='cols' value='dotted' />
          </style-rule>
          <style-rule element='gridline'>
            <format attr='stroke-size' scope='cols' value='0' />
            <format attr='line-visibility' scope='cols' value='off' />
          </style-rule>
          <style-rule element='zeroline'>
            <format attr='stroke-size' scope='cols' value='0' />
            <format attr='line-visibility' scope='cols' value='off' />
          </style-rule>
          <style-rule element='title'>
            <format attr='color' value='#f5f5f5' />
          </style-rule>
          <style-rule element='map'>
            <format attr='washout' value='0.0' />
          </style-rule>
          <_.fcp.MarkAnimation.true...style-rule element='animation'>
            <format attr='animation-duration' value='0.0010000000474974513' />
            <format attr='animation-style' value='as-synced' />
          </_.fcp.MarkAnimation.true...style-rule>
        </style>
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
            <encodings>
              <text column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[none:State/UnionTerritory:nk]' />
              <color column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[rank:sum:Confirmed:qk]' />
              <geometry column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[Geometry (generated)]' />
            </encodings>
            <style>
              <style-rule element='mark'>
                <format attr='mark-transparency' value='255' />
                <format attr='mark-labels-show' value='true' />
                <format attr='mark-labels-cull' value='true' />
              </style-rule>
            </style>
          </pane>
        </panes>
        <rows>[federated.0bd2dna07rjett15ohm5x19xsxxb].[Latitude (generated)]</rows>
        <cols>[federated.0bd2dna07rjett15ohm5x19xsxxb].[Longitude (generated)]</cols>
        <pages>
          <column>[federated.0bd2dna07rjett15ohm5x19xsxxb].[md:Date:ok]</column>
        </pages>
      </table>
      <simple-id uuid='{252A5476-C7B4-42A8-B971-AD1690CE2C14}' />
    </worksheet>
    <worksheet name='Number (Total)'>
      <layout-options>
        <title>
          <formatted-text />
        </title>
      </layout-options>
      <table>
        <view>
          <datasources>
            <datasource caption='Sheet2 (Task-6_Dataset)' name='federated.0bd2dna07rjett15ohm5x19xsxxb' />
          </datasources>
          <mapsources>
            <mapsource name='Tableau' />
          </mapsources>
          <datasource-dependencies datasource='federated.0bd2dna07rjett15ohm5x19xsxxb'>
            <column datatype='integer' name='[Confirmed]' role='measure' type='quantitative' />
            <column datatype='date' name='[Date]' role='dimension' type='ordinal' />
            <column-instance column='[Date]' derivation='MDY' name='[md:Date:ok]' pivot='key' type='ordinal' />
            <column-instance column='[Confirmed]' derivation='Sum' name='[sum:Confirmed:qk]' pivot='key' type='quantitative' />
          </datasource-dependencies>
          <filter class='categorical' column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[md:Date:ok]'>
            <groupfilter from='20200130' function='range' level='[md:Date:ok]' to='20201007' user:ui-domain='relevant' user:ui-enumeration='inclusive' user:ui-marker='enumerate' />
          </filter>
          <slices>
            <column>[federated.0bd2dna07rjett15ohm5x19xsxxb].[md:Date:ok]</column>
          </slices>
          <aggregation value='true' />
        </view>
        <style>
          <style-rule element='axis'>
            <format attr='stroke-size' scope='cols' value='2' />
          </style-rule>
          <style-rule element='header'>
            <format attr='border-style' data-class='total' scope='cols' value='dashed' />
          </style-rule>
          <style-rule element='mark'>
            <encoding attr='color' field='[federated.0bd2dna07rjett15ohm5x19xsxxb].[sum:Confirmed:qk]' palette='tableau-map-temperatur' type='interpolated' />
          </style-rule>
          <style-rule element='pane'>
            <format attr='border-style' data-class='total' scope='cols' value='dotted' />
          </style-rule>
          <style-rule element='table'>
            <format attr='background-color' value='#000000' />
          </style-rule>
          <style-rule element='worksheet'>
            <format attr='display-field-labels' scope='rows' value='false' />
            <format attr='color' value='#ffffff' />
          </style-rule>
          <style-rule element='refline'>
            <format attr='line-visibility' scope='cols' value='on' />
            <format attr='line-pattern-only' scope='cols' value='dotted' />
          </style-rule>
          <style-rule element='gridline'>
            <format attr='stroke-size' scope='cols' value='0' />
            <format attr='line-visibility' scope='cols' value='off' />
          </style-rule>
          <style-rule element='zeroline'>
            <format attr='stroke-size' scope='cols' value='0' />
            <format attr='line-visibility' scope='cols' value='off' />
          </style-rule>
          <style-rule element='title'>
            <format attr='color' value='#f5f5f5' />
          </style-rule>
          <style-rule element='map'>
            <format attr='washout' value='0.0' />
          </style-rule>
          <_.fcp.MarkAnimation.true...style-rule element='animation'>
            <format attr='animation-duration' value='0.0010000000474974513' />
            <format attr='animation-style' value='as-synced' />
          </_.fcp.MarkAnimation.true...style-rule>
        </style>
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Pie' />
            <mark-sizing mark-sizing-setting='marks-scaling-off' />
            <encodings>
              <text column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[sum:Confirmed:qk]' />
              <lod column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[sum:Confirmed:qk]' />
            </encodings>
            <style>
              <style-rule element='mark'>
                <format attr='mark-labels-cull' value='true' />
                <format attr='mark-labels-line-first' value='true' />
                <format attr='mark-labels-line-last' value='true' />
                <format attr='mark-labels-range-min' value='true' />
                <format attr='mark-labels-range-max' value='true' />
                <format attr='mark-labels-mode' value='all' />
                <format attr='mark-labels-range-scope' value='pane' />
                <format attr='mark-labels-range-field' value='' />
                <format attr='size' value='0.0099999997764825821' />
                <format attr='mark-labels-show' value='true' />
              </style-rule>
            </style>
          </pane>
        </panes>
        <rows />
        <cols />
        <pages>
          <column>[federated.0bd2dna07rjett15ohm5x19xsxxb].[md:Date:ok]</column>
        </pages>
        <mark-labels>
          <mark-label id='0'>
            <tuple-reference>
              <tuple-descriptor>
                <pane-descriptor>
                  <x-fields />
                  <y-fields />
                </pane-descriptor>
                <columns>
                  <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[md:Date:ok]</field>
                  <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[sum:Confirmed:qk]</field>
                </columns>
              </tuple-descriptor>
              <tuple>
                <value>20201007</value>
                <value>6757131</value>
              </tuple>
            </tuple-reference>
            <label-position x='36' y='30' />
          </mark-label>
        </mark-labels>
      </table>
      <simple-id uuid='{D7EAC061-4A2F-4D9A-AB29-F45894CF8DA4}' />
    </worksheet>
    <worksheet name='Total Cases'>
      <layout-options>
        <title>
          <formatted-text>
            <run bold='true' fontsize='9'>Rank</run>
            <run>Æ&#10;</run>
          </formatted-text>
        </title>
      </layout-options>
      <table>
        <view>
          <datasources>
            <datasource caption='Sheet2 (Task-6_Dataset)' name='federated.0bd2dna07rjett15ohm5x19xsxxb' />
          </datasources>
          <mapsources>
            <mapsource name='Tableau' />
          </mapsources>
          <datasource-dependencies datasource='federated.0bd2dna07rjett15ohm5x19xsxxb'>
            <column caption='Rank' datatype='integer' name='[Calculation_820218120432779264]' role='measure' type='quantitative'>
              <calculation class='tableau' formula='RANK_UNIQUE(SUM([Confirmed]))'>
                <table-calc ordering-type='Rows' />
              </calculation>
            </column>
            <column datatype='integer' name='[Confirmed]' role='measure' type='quantitative' />
            <column datatype='date' name='[Date]' role='dimension' type='ordinal' />
            <column caption='State/UnionTerritory1' datatype='string' name='[State/UnionTerritory]' role='dimension' semantic-role='[State].[Name]' type='nominal'>
              <semantic-values semantic-role='[State].[Name]'>
                <semantic-value key='&quot;Dadra and Nagar Haveli and Daman and Diu&quot;' value='&quot;Dadra and Nagar Haveli&quot;' />
              </semantic-values>
            </column>
            <column-instance column='[Confirmed]' derivation='Max' name='[max:Confirmed:qk]' pivot='key' type='quantitative' />
            <column-instance column='[Date]' derivation='Max' name='[max:Date:qk]' pivot='key' type='quantitative' />
            <column-instance column='[Date]' derivation='MDY' name='[md:Date:ok]' pivot='key' type='ordinal' />
            <column-instance column='[State/UnionTerritory]' derivation='None' name='[none:State/UnionTerritory:nk]' pivot='key' type='nominal' />
            <column-instance column='[Confirmed]' derivation='Sum' name='[sum:Confirmed:qk]' pivot='key' type='quantitative' />
            <column-instance column='[Calculation_820218120432779264]' derivation='User' name='[usr:Calculation_820218120432779264:ok:2]' pivot='key' type='ordinal'>
              <table-calc ordering-field='[federated.0bd2dna07rjett15ohm5x19xsxxb].[State/UnionTerritory]' ordering-type='Field' />
            </column-instance>
          </datasource-dependencies>
          <filter class='categorical' column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[Exclusions (MDY(Date),State/UnionTerritory1)]'>
            <groupfilter function='except' user:ui-domain='database' user:ui-enumeration='exclusive' user:ui-marker='enumerate'>
              <groupfilter function='crossjoin'>
                <groupfilter function='level-members' level='[md:Date:ok]' />
                <groupfilter function='level-members' level='[none:State/UnionTerritory:nk]' />
              </groupfilter>
              <groupfilter function='union'>
                <groupfilter function='crossjoin'>
                  <groupfilter function='member' level='[md:Date:ok]' member='20200706' />
                  <groupfilter function='member' level='[none:State/UnionTerritory:nk]' member='&quot;Assam&quot;' />
                </groupfilter>
                <groupfilter function='crossjoin'>
                  <groupfilter function='member' level='[md:Date:ok]' member='20200711' />
                  <groupfilter function='member' level='[none:State/UnionTerritory:nk]' member='&quot;Cases being reassigned to states&quot;' />
                </groupfilter>
              </groupfilter>
            </groupfilter>
          </filter>
          <filter class='quantitative' column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Confirmed:qk]' included-values='in-range-or-null'>
            <min>0</min>
          </filter>
          <filter class='categorical' column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[none:State/UnionTerritory:nk]'>
            <groupfilter function='union' user:ui-domain='relevant' user:ui-enumeration='inclusive' user:ui-marker='enumerate'>
              <groupfilter from='&quot;Andaman and Nicobar Islands&quot;' function='range' level='[none:State/UnionTerritory:nk]' to='&quot;Nagaland&quot;' />
              <groupfilter from='&quot;Odisha&quot;' function='range' level='[none:State/UnionTerritory:nk]' to='&quot;Telangana&quot;' />
              <groupfilter function='member' level='[none:State/UnionTerritory:nk]' member='&quot;Telengana&quot;' />
              <groupfilter from='&quot;Tripura&quot;' function='range' level='[none:State/UnionTerritory:nk]' to='&quot;West Bengal&quot;' />
            </groupfilter>
          </filter>
          <slices>
            <column>[federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Confirmed:qk]</column>
            <column>[federated.0bd2dna07rjett15ohm5x19xsxxb].[none:State/UnionTerritory:nk]</column>
            <column>[federated.0bd2dna07rjett15ohm5x19xsxxb].[Exclusions (MDY(Date),State/UnionTerritory1)]</column>
          </slices>
          <aggregation value='true' />
        </view>
        <style>
          <style-rule element='axis'>
            <format attr='stroke-size' scope='cols' value='2' />
            <format attr='title' class='0' field='[federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Confirmed:qk]' scope='cols' value='Total Confirmed Cases' />
            <encoding attr='space' class='0' field='[federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Confirmed:qk]' field-type='quantitative' scale='log' scope='cols' type='space' />
          </style-rule>
          <style-rule element='header'>
            <format attr='border-style' data-class='total' scope='cols' value='dashed' />
          </style-rule>
          <style-rule element='mark'>
            <encoding attr='color' field='[federated.0bd2dna07rjett15ohm5x19xsxxb].[sum:Confirmed:qk]' palette='tableau-map-temperatur' type='interpolated' />
          </style-rule>
          <style-rule element='pane'>
            <format attr='border-style' data-class='total' scope='cols' value='dotted' />
          </style-rule>
          <style-rule element='table'>
            <format attr='background-color' value='#000000' />
          </style-rule>
          <style-rule element='worksheet'>
            <format attr='display-field-labels' scope='rows' value='false' />
            <format attr='color' value='#ffffff' />
          </style-rule>
          <style-rule element='refline'>
            <format attr='line-visibility' scope='cols' value='on' />
            <format attr='line-pattern-only' scope='cols' value='dotted' />
          </style-rule>
          <style-rule element='gridline'>
            <format attr='stroke-size' scope='cols' value='0' />
            <format attr='line-visibility' scope='cols' value='off' />
          </style-rule>
          <style-rule element='zeroline'>
            <format attr='stroke-size' scope='cols' value='0' />
            <format attr='line-visibility' scope='cols' value='off' />
          </style-rule>
          <style-rule element='title'>
            <format attr='color' value='#f5f5f5' />
          </style-rule>
          <style-rule element='map'>
            <format attr='washout' value='0.0' />
          </style-rule>
          <_.fcp.MarkAnimation.true...style-rule element='animation'>
            <format attr='animation-duration' value='0.0010000000474974513' />
            <format attr='animation-style' value='as-synced' />
          </_.fcp.MarkAnimation.true...style-rule>
        </style>
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
            <encodings>
              <color column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[sum:Confirmed:qk]' />
              <text column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[none:State/UnionTerritory:nk]' />
              <lod column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[none:State/UnionTerritory:nk]' />
            </encodings>
            <label-data column='[federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Date:qk]' />
            <style>
              <style-rule element='mark'>
                <format attr='mark-labels-show' value='true' />
                <format attr='mark-transparency' value='255' />
                <format attr='mark-labels-cull' value='false' />
                <format attr='mark-labels-mode' value='most-recent' />
              </style-rule>
            </style>
          </pane>
        </panes>
        <rows>[federated.0bd2dna07rjett15ohm5x19xsxxb].[usr:Calculation_820218120432779264:ok:2]</rows>
        <cols>[federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Confirmed:qk]</cols>
        <pages>
          <column>[federated.0bd2dna07rjett15ohm5x19xsxxb].[md:Date:ok]</column>
        </pages>
      </table>
      <simple-id uuid='{487F4F7B-E6AA-4FF6-B0E3-60886DB9C40E}' />
    </worksheet>
  </worksheets>
  <dashboards>
    <dashboard name='Dashboard '>
      <layout-options>
        <title>
          <formatted-text>
            <run bold='true' fontalignment='1' fontcolor='#e15759' fontname='Tw Cen MT Condensed Extra Bold' fontsize='28'>Timeline Analysis (India) : Covid-19 </run>
          </formatted-text>
        </title>
      </layout-options>
      <style>
        <style-rule element='table'>
          <format attr='background-color' value='#000000' />
        </style-rule>
      </style>
      <size maxheight='900' maxwidth='1880' minheight='900' minwidth='1880' preset-index='16' sizing-mode='fixed' />
      <zones>
        <zone _.fcp.SetMembershipControl.false...type='layout-basic' _.fcp.SetMembershipControl.true...type-v2='layout-basic' h='100000' id='8' w='100000' x='0' y='0'>
          <zone _.fcp.SetMembershipControl.false...type='layout-flow' _.fcp.SetMembershipControl.true...type-v2='layout-flow' h='98222' id='15' param='horz' w='99148' x='426' y='889'>
            <zone _.fcp.SetMembershipControl.false...type='layout-flow' _.fcp.SetMembershipControl.true...type-v2='layout-flow' h='98222' id='11' param='vert' w='75425' x='426' y='889'>
              <zone _.fcp.SetMembershipControl.false...type='title' _.fcp.SetMembershipControl.true...type-v2='title' fixed-size='53' h='6778' id='12' is-fixed='true' w='75425' x='426' y='889'>
                <zone-style>
                  <format attr='border-color' value='#000000' />
                  <format attr='border-style' value='none' />
                  <format attr='border-width' value='0' />
                  <format attr='margin' value='4' />
                </zone-style>
              </zone>
              <zone _.fcp.SetMembershipControl.false...type='layout-basic' _.fcp.SetMembershipControl.true...type-v2='layout-basic' fixed-size='837' h='91444' id='9' is-fixed='true' w='75425' x='426' y='7667' />
            </zone>
            <zone _.fcp.SetMembershipControl.false...type='layout-flow' _.fcp.SetMembershipControl.true...type-v2='layout-flow' fixed-size='446' h='98222' id='14' is-fixed='true' param='vert' w='23723' x='75851' y='889'>
              <zone _.fcp.SetMembershipControl.false...type='currpage' _.fcp.SetMembershipControl.true...type-v2='currpage' count='5' fixed-size='124' h='14667' id='16' is-fixed='true' name='Map cases' name1='Cure vs Death plot' name2='Total Cases' name3='Number (Total)' name4='Cured' name5='Deceased' synchronized='1' w='23723' x='75851' y='889'>
                <zone-style>
                  <format attr='border-color' value='#000000' />
                  <format attr='border-style' value='none' />
                  <format attr='border-width' value='0' />
                  <format attr='margin' value='4' />
                </zone-style>
              </zone>
            </zone>
          </zone>
          <zone-style>
            <format attr='border-color' value='#000000' />
            <format attr='border-style' value='none' />
            <format attr='border-width' value='0' />
            <format attr='margin' value='8' />
          </zone-style>
        </zone>
        <zone h='88889' id='6' name='Map cases' w='35160' x='160' y='6000' />
        <zone h='49222' id='13' name='Cure vs Death plot' w='39149' x='35319' y='8667' />
        <zone h='47889' id='17' name='Total Cases' w='39415' x='35160' y='57778' />
        <zone _.fcp.SetMembershipControl.false...type='color' _.fcp.SetMembershipControl.true...type-v2='color' h='11111' id='18' name='Total Cases' pane-specification-id='0' param='[federated.0bd2dna07rjett15ohm5x19xsxxb].[sum:Confirmed:qk]' w='37979' x='-160' y='95667' />
        <zone _.fcp.SetMembershipControl.false...type='text' _.fcp.SetMembershipControl.true...type-v2='text' forceUpdate='true' h='4556' id='23' w='15000' x='81383' y='36444'>
          <formatted-text>
            <run bold='true' fontcolor='#ff9da7' fontname='Tw Cen MT Condensed Extra Bold' fontsize='18'>__Total Cases__</run>
          </formatted-text>
        </zone>
        <zone _.fcp.SetMembershipControl.false...type='bitmap' _.fcp.SetMembershipControl.true...type-v2='bitmap' h='5889' id='25' is-centered='0' is-scaled='1' param='C:/Users/kriti/Desktop/1.PNG' w='23085' x='75638' y='45667' />
        <zone _.fcp.SetMembershipControl.false...type='text' _.fcp.SetMembershipControl.true...type-v2='text' forceUpdate='true' h='3667' id='31' w='16277' x='80000' y='58556'>
          <formatted-text>
            <run bold='true' fontcolor='#ff9da7' fontname='Tw Cen MT Condensed Extra Bold' fontsize='18'>__Cured Patients__</run>
          </formatted-text>
        </zone>
        <zone _.fcp.SetMembershipControl.false...type='text' _.fcp.SetMembershipControl.true...type-v2='text' forceUpdate='true' h='4333' id='34' w='19255' x='78777' y='80444'>
          <formatted-text>
            <run bold='true' fontcolor='#ff9da7' fontname='Tw Cen MT Condensed Extra Bold' fontsize='18'>__Deceased Patients__</run>
          </formatted-text>
        </zone>
        <zone _.fcp.SetMembershipControl.false...type='bitmap' _.fcp.SetMembershipControl.true...type-v2='bitmap' h='6333' id='61' is-centered='0' is-scaled='1' param='Z:/GithubProjects/The-Sparks-Foundation-Tasks/img/2.PNG' w='23883' x='75532' y='45778' />
        <zone h='19667' id='62' name='Number (Total)' w='9574' x='83936' y='39000' />
        <zone _.fcp.SetMembershipControl.false...type='bitmap' _.fcp.SetMembershipControl.true...type-v2='bitmap' h='31556' id='63' is-centered='0' is-scaled='1' param='Z:/GithubProjects/The-Sparks-Foundation-Tasks/img/2.PNG' w='23723' x='75851' y='69778' />
        <zone h='20222' id='64' name='Cured' w='8777' x='84309' y='61556' />
        <zone _.fcp.SetMembershipControl.false...type='bitmap' _.fcp.SetMembershipControl.true...type-v2='bitmap' h='31556' id='65' is-centered='0' is-scaled='1' param='Z:/GithubProjects/The-Sparks-Foundation-Tasks/img/2.PNG' w='23457' x='75904' y='91333' />
        <zone h='20889' id='66' name='Deceased' w='9149' x='84415' y='83556' />
      </zones>
      <devicelayouts>
        <devicelayout auto-generated='true' name='Phone'>
          <layout-options>
            <title>
              <formatted-text>
                <run bold='true' fontalignment='1' fontcolor='#e15759' fontname='Tw Cen MT Condensed Extra Bold' fontsize='28'>Timeline Analysis (India) : Covid-19 </run>
              </formatted-text>
            </title>
          </layout-options>
          <size maxheight='2550' minheight='2550' sizing-mode='vscroll' />
          <zones>
            <zone _.fcp.SetMembershipControl.false...type='layout-basic' _.fcp.SetMembershipControl.true...type-v2='layout-basic' h='100000' id='68' w='100000' x='0' y='0'>
              <zone _.fcp.SetMembershipControl.false...type='layout-flow' _.fcp.SetMembershipControl.true...type-v2='layout-flow' h='98222' id='67' param='vert' w='99148' x='426' y='889'>
                <zone _.fcp.SetMembershipControl.false...type='title' _.fcp.SetMembershipControl.true...type-v2='title' fixed-size='53' h='6778' id='12' w='75425' x='426' y='889'>
                  <zone-style>
                    <format attr='border-color' value='#000000' />
                    <format attr='border-style' value='none' />
                    <format attr='border-width' value='0' />
                    <format attr='margin' value='4' />
                    <format attr='padding' value='0' />
                  </zone-style>
                </zone>
                <zone fixed-size='280' h='88889' id='6' is-fixed='true' name='Map cases' w='35160' x='160' y='6000'>
                  <zone-style>
                    <format attr='border-color' value='#000000' />
                    <format attr='border-style' value='none' />
                    <format attr='border-width' value='0' />
                    <format attr='margin' value='4' />
                    <format attr='padding' value='0' />
                  </zone-style>
                </zone>
                <zone fixed-size='280' h='49222' id='13' is-fixed='true' name='Cure vs Death plot' w='39149' x='35319' y='8667'>
                  <zone-style>
                    <format attr='border-color' value='#000000' />
                    <format attr='border-style' value='none' />
                    <format attr='border-width' value='0' />
                    <format attr='margin' value='4' />
                    <format attr='padding' value='0' />
                  </zone-style>
                </zone>
                <zone _.fcp.SetMembershipControl.false...type='text' _.fcp.SetMembershipControl.true...type-v2='text' forceUpdate='true' h='4556' id='23' w='15000' x='81383' y='36444'>
                  <formatted-text>
                    <run bold='true' fontcolor='#ff9da7' fontname='Tw Cen MT Condensed Extra Bold' fontsize='18'>__Total Cases__</run>
                  </formatted-text>
                  <zone-style>
                    <format attr='border-color' value='#000000' />
                    <format attr='border-style' value='none' />
                    <format attr='border-width' value='0' />
                    <format attr='margin' value='4' />
                    <format attr='padding' value='0' />
                  </zone-style>
                </zone>
                <zone fixed-size='177' h='19667' id='62' is-fixed='true' name='Number (Total)' w='9574' x='83936' y='39000'>
                  <zone-style>
                    <format attr='border-color' value='#000000' />
                    <format attr='border-style' value='none' />
                    <format attr='border-width' value='0' />
                    <format attr='margin' value='4' />
                    <format attr='padding' value='0' />
                  </zone-style>
                </zone>
                <zone _.fcp.SetMembershipControl.false...type='bitmap' _.fcp.SetMembershipControl.true...type-v2='bitmap' fixed-size='53' h='5889' id='25' is-centered='0' is-fixed='true' is-scaled='1' param='C:/Users/kriti/Desktop/1.PNG' w='23085' x='75638' y='45667'>
                  <zone-style>
                    <format attr='border-color' value='#000000' />
                    <format attr='border-style' value='none' />
                    <format attr='border-width' value='0' />
                    <format attr='margin' value='4' />
                    <format attr='padding' value='0' />
                  </zone-style>
                </zone>
                <zone _.fcp.SetMembershipControl.false...type='bitmap' _.fcp.SetMembershipControl.true...type-v2='bitmap' fixed-size='57' h='6333' id='61' is-centered='0' is-fixed='true' is-scaled='1' param='Z:/GithubProjects/The-Sparks-Foundation-Tasks/img/2.PNG' w='23883' x='75532' y='45778'>
                  <zone-style>
                    <format attr='border-color' value='#000000' />
                    <format attr='border-style' value='none' />
                    <format attr='border-width' value='0' />
                    <format attr='margin' value='4' />
                    <format attr='padding' value='0' />
                  </zone-style>
                </zone>
                <zone fixed-size='280' h='47889' id='17' is-fixed='true' name='Total Cases' w='39415' x='35160' y='57778'>
                  <zone-style>
                    <format attr='border-color' value='#000000' />
                    <format attr='border-style' value='none' />
                    <format attr='border-width' value='0' />
                    <format attr='margin' value='4' />
                    <format attr='padding' value='0' />
                  </zone-style>
                </zone>
                <zone _.fcp.SetMembershipControl.false...type='color' _.fcp.SetMembershipControl.true...type-v2='color' h='11111' id='18' name='Total Cases' pane-specification-id='0' param='[federated.0bd2dna07rjett15ohm5x19xsxxb].[sum:Confirmed:qk]' w='37979' x='-160' y='95667'>
                  <zone-style>
                    <format attr='border-color' value='#000000' />
                    <format attr='border-style' value='none' />
                    <format attr='border-width' value='0' />
                    <format attr='margin' value='4' />
                    <format attr='padding' value='0' />
                  </zone-style>
                </zone>
                <zone _.fcp.SetMembershipControl.false...type='text' _.fcp.SetMembershipControl.true...type-v2='text' forceUpdate='true' h='3667' id='31' w='16277' x='80000' y='58556'>
                  <formatted-text>
                    <run bold='true' fontcolor='#ff9da7' fontname='Tw Cen MT Condensed Extra Bold' fontsize='18'>__Cured Patients__</run>
                  </formatted-text>
                  <zone-style>
                    <format attr='border-color' value='#000000' />
                    <format attr='border-style' value='none' />
                    <format attr='border-width' value='0' />
                    <format attr='margin' value='4' />
                    <format attr='padding' value='0' />
                  </zone-style>
                </zone>
                <zone fixed-size='182' h='20222' id='64' is-fixed='true' name='Cured' w='8777' x='84309' y='61556'>
                  <zone-style>
                    <format attr='border-color' value='#000000' />
                    <format attr='border-style' value='none' />
                    <format attr='border-width' value='0' />
                    <format attr='margin' value='4' />
                    <format attr='padding' value='0' />
                  </zone-style>
                </zone>
                <zone _.fcp.SetMembershipControl.false...type='bitmap' _.fcp.SetMembershipControl.true...type-v2='bitmap' fixed-size='280' h='31556' id='63' is-centered='0' is-fixed='true' is-scaled='1' param='Z:/GithubProjects/The-Sparks-Foundation-Tasks/img/2.PNG' w='23723' x='75851' y='69778'>
                  <zone-style>
                    <format attr='border-color' value='#000000' />
                    <format attr='border-style' value='none' />
                    <format attr='border-width' value='0' />
                    <format attr='margin' value='4' />
                    <format attr='padding' value='0' />
                  </zone-style>
                </zone>
                <zone _.fcp.SetMembershipControl.false...type='text' _.fcp.SetMembershipControl.true...type-v2='text' forceUpdate='true' h='4333' id='34' w='19255' x='78777' y='80444'>
                  <formatted-text>
                    <run bold='true' fontcolor='#ff9da7' fontname='Tw Cen MT Condensed Extra Bold' fontsize='18'>__Deceased Patients__</run>
                  </formatted-text>
                  <zone-style>
                    <format attr='border-color' value='#000000' />
                    <format attr='border-style' value='none' />
                    <format attr='border-width' value='0' />
                    <format attr='margin' value='4' />
                    <format attr='padding' value='0' />
                  </zone-style>
                </zone>
                <zone fixed-size='188' h='20889' id='66' is-fixed='true' name='Deceased' w='9149' x='84415' y='83556'>
                  <zone-style>
                    <format attr='border-color' value='#000000' />
                    <format attr='border-style' value='none' />
                    <format attr='border-width' value='0' />
                    <format attr='margin' value='4' />
                    <format attr='padding' value='0' />
                  </zone-style>
                </zone>
                <zone _.fcp.SetMembershipControl.false...type='bitmap' _.fcp.SetMembershipControl.true...type-v2='bitmap' fixed-size='280' h='31556' id='65' is-centered='0' is-fixed='true' is-scaled='1' param='Z:/GithubProjects/The-Sparks-Foundation-Tasks/img/2.PNG' w='23457' x='75904' y='91333'>
                  <zone-style>
                    <format attr='border-color' value='#000000' />
                    <format attr='border-style' value='none' />
                    <format attr='border-width' value='0' />
                    <format attr='margin' value='4' />
                    <format attr='padding' value='0' />
                  </zone-style>
                </zone>
                <zone _.fcp.SetMembershipControl.false...type='currpage' _.fcp.SetMembershipControl.true...type-v2='currpage' count='5' fixed-size='124' h='14667' id='16' name='Map cases' name1='Cure vs Death plot' name2='Total Cases' name3='Number (Total)' name4='Cured' name5='Deceased' synchronized='1' w='23723' x='75851' y='889'>
                  <zone-style>
                    <format attr='border-color' value='#000000' />
                    <format attr='border-style' value='none' />
                    <format attr='border-width' value='0' />
                    <format attr='margin' value='4' />
                    <format attr='padding' value='0' />
                  </zone-style>
                </zone>
              </zone>
              <zone-style>
                <format attr='border-color' value='#000000' />
                <format attr='border-style' value='none' />
                <format attr='border-width' value='0' />
                <format attr='margin' value='8' />
              </zone-style>
            </zone>
          </zones>
        </devicelayout>
      </devicelayouts>
      <simple-id uuid='{C3C13C93-3356-415A-8CD7-206F50A20E54}' />
    </dashboard>
    <dashboard name='Datasheet'>
      <layout-options>
        <title>
          <formatted-text>
            <run fontalignment='1' fontcolor='#f28e2b' fontname='Tw Cen MT Condensed Extra Bold' fontsize='36'>&lt;Sheet Name&gt;</run>
          </formatted-text>
        </title>
      </layout-options>
      <style>
        <style-rule element='table'>
          <format attr='background-color' value='#000000' />
        </style-rule>
      </style>
      <size maxheight='900' maxwidth='1880' minheight='900' minwidth='1880' sizing-mode='fixed' />
      <zones>
        <zone _.fcp.SetMembershipControl.false...type='layout-basic' _.fcp.SetMembershipControl.true...type-v2='layout-basic' h='100000' id='4' w='100000' x='0' y='0'>
          <zone _.fcp.SetMembershipControl.false...type='layout-flow' _.fcp.SetMembershipControl.true...type-v2='layout-flow' h='98222' id='5' param='vert' w='99148' x='426' y='889'>
            <zone _.fcp.SetMembershipControl.false...type='title' _.fcp.SetMembershipControl.true...type-v2='title' h='9556' id='7' w='99148' x='426' y='889'>
              <zone-style>
                <format attr='border-color' value='#000000' />
                <format attr='border-style' value='none' />
                <format attr='border-width' value='0' />
                <format attr='margin' value='4' />
              </zone-style>
            </zone>
            <zone _.fcp.SetMembershipControl.false...type='bitmap' _.fcp.SetMembershipControl.true...type-v2='bitmap' fixed-size='684' forceUpdate='true' h='76889' id='8' is-fixed='true' param='Z:/GithubProjects/The-Sparks-Foundation-Tasks/img/sheet.PNG' w='99148' x='426' y='10445'>
              <zone-style>
                <format attr='border-color' value='#000000' />
                <format attr='border-style' value='none' />
                <format attr='border-width' value='0' />
                <format attr='margin' value='4' />
              </zone-style>
            </zone>
          </zone>
          <zone-style>
            <format attr='border-color' value='#000000' />
            <format attr='border-style' value='none' />
            <format attr='border-width' value='0' />
            <format attr='margin' value='8' />
          </zone-style>
        </zone>
      </zones>
      <devicelayouts>
        <devicelayout auto-generated='true' name='Phone'>
          <layout-options>
            <title>
              <formatted-text>
                <run fontalignment='1' fontcolor='#f28e2b' fontname='Tw Cen MT Condensed Extra Bold' fontsize='36'>&lt;Sheet Name&gt;</run>
              </formatted-text>
            </title>
          </layout-options>
          <size maxheight='700' minheight='700' sizing-mode='vscroll' />
          <zones>
            <zone _.fcp.SetMembershipControl.false...type='layout-basic' _.fcp.SetMembershipControl.true...type-v2='layout-basic' h='100000' id='16' w='100000' x='0' y='0'>
              <zone _.fcp.SetMembershipControl.false...type='layout-flow' _.fcp.SetMembershipControl.true...type-v2='layout-flow' h='98222' id='15' param='vert' w='99148' x='426' y='889'>
                <zone _.fcp.SetMembershipControl.false...type='title' _.fcp.SetMembershipControl.true...type-v2='title' h='9556' id='7' w='99148' x='426' y='889'>
                  <zone-style>
                    <format attr='border-color' value='#000000' />
                    <format attr='border-style' value='none' />
                    <format attr='border-width' value='0' />
                    <format attr='margin' value='4' />
                    <format attr='padding' value='0' />
                  </zone-style>
                </zone>
                <zone _.fcp.SetMembershipControl.false...type='bitmap' _.fcp.SetMembershipControl.true...type-v2='bitmap' fixed-size='280' forceUpdate='true' h='76889' id='8' is-fixed='true' param='Z:/GithubProjects/The-Sparks-Foundation-Tasks/img/sheet.PNG' w='99148' x='426' y='10445'>
                  <zone-style>
                    <format attr='border-color' value='#000000' />
                    <format attr='border-style' value='none' />
                    <format attr='border-width' value='0' />
                    <format attr='margin' value='4' />
                    <format attr='padding' value='0' />
                  </zone-style>
                </zone>
              </zone>
              <zone-style>
                <format attr='border-color' value='#000000' />
                <format attr='border-style' value='none' />
                <format attr='border-width' value='0' />
                <format attr='margin' value='8' />
              </zone-style>
            </zone>
          </zones>
        </devicelayout>
      </devicelayouts>
      <simple-id uuid='{5608FA65-6DBA-40C1-9C39-072CE8E9AFC4}' />
    </dashboard>
    <dashboard name='Introduction'>
      <layout-options>
        <title>
          <formatted-text>
            <run fontalignment='1' fontcolor='#e15759' fontname='Tw Cen MT Condensed Extra Bold' fontsize='48'>Author : Kritika Srivastava</run>
          </formatted-text>
        </title>
      </layout-options>
      <style>
        <style-rule element='table'>
          <format attr='background-color' value='#333333' />
        </style-rule>
      </style>
      <size maxheight='900' maxwidth='1880' minheight='900' minwidth='1880' sizing-mode='fixed' />
      <zones>
        <zone _.fcp.SetMembershipControl.false...type='layout-basic' _.fcp.SetMembershipControl.true...type-v2='layout-basic' h='100000' id='4' w='100000' x='0' y='0'>
          <zone _.fcp.SetMembershipControl.false...type='layout-flow' _.fcp.SetMembershipControl.true...type-v2='layout-flow' h='98222' id='5' param='vert' w='99148' x='426' y='889'>
            <zone _.fcp.SetMembershipControl.false...type='title' _.fcp.SetMembershipControl.true...type-v2='title' h='12445' id='7' w='99148' x='426' y='889'>
              <zone-style>
                <format attr='border-color' value='#000000' />
                <format attr='border-style' value='none' />
                <format attr='border-width' value='0' />
                <format attr='margin' value='4' />
              </zone-style>
            </zone>
            <zone _.fcp.SetMembershipControl.false...type='layout-basic' _.fcp.SetMembershipControl.true...type-v2='layout-basic' h='85777' id='6' w='99148' x='426' y='13334' />
          </zone>
          <zone-style>
            <format attr='border-color' value='#000000' />
            <format attr='border-style' value='none' />
            <format attr='border-width' value='0' />
            <format attr='margin' value='8' />
          </zone-style>
        </zone>
        <zone _.fcp.SetMembershipControl.false...type='text' _.fcp.SetMembershipControl.true...type-v2='text' forceUpdate='true' h='80000' id='9' w='83564' x='10106' y='19667'>
          <formatted-text>
            <run bold='true' fontalignment='1' fontcolor='#f28e2b' fontname='Tableau Semibold' fontsize='28' underline='true'>Task 6 - Timeline Analysis : Covid 19</run>
            <run fontalignment='1'>Æ&#10;&#10;&#10;</run>
            <run>Æ&#10;</run>
            <run bold='true' fontcolor='#f1ce63' fontname='Times New Roman' fontsize='28'>Objective</run>
            <run fontcolor='#c0c0c0' fontname='Times New Roman' fontsize='28'> - </run>
            <run>Æ&#10;&#10;</run>
            <run fontcolor='#c0c0c0' fontname='Times New Roman' fontsize='28'>Use animation, timeline and annotations to create attractive and interactive dashboard showing spread of Covid 19 cases in your country .</run>
            <run>Æ&#10;&#10;&#10;&#10;</run>
            <run fontalignment='1'>Æ&#10;</run>
            <run bold='true' fontalignment='1' fontcolor='#8cd17d' fontname='Tableau Semibold' fontsize='28'>GRIP@ THE SPARKS FOUNDATION</run>
          </formatted-text>
        </zone>
        <zone _.fcp.SetMembershipControl.false...type='bitmap' _.fcp.SetMembershipControl.true...type-v2='bitmap' h='31556' id='10' is-centered='0' is-scaled='1' param='C:/Users/kriti/Desktop/logo_small.png' w='11862' x='80319' y='64667' />
      </zones>
      <devicelayouts>
        <devicelayout auto-generated='true' name='Phone'>
          <layout-options>
            <title>
              <formatted-text>
                <run fontalignment='1' fontcolor='#e15759' fontname='Tw Cen MT Condensed Extra Bold' fontsize='48'>Author : Kritika Srivastava</run>
              </formatted-text>
            </title>
          </layout-options>
          <size maxheight='700' minheight='700' sizing-mode='vscroll' />
          <zones>
            <zone _.fcp.SetMembershipControl.false...type='layout-basic' _.fcp.SetMembershipControl.true...type-v2='layout-basic' h='100000' id='26' w='100000' x='0' y='0'>
              <zone _.fcp.SetMembershipControl.false...type='layout-flow' _.fcp.SetMembershipControl.true...type-v2='layout-flow' h='98222' id='25' param='vert' w='99148' x='426' y='889'>
                <zone _.fcp.SetMembershipControl.false...type='title' _.fcp.SetMembershipControl.true...type-v2='title' h='12445' id='7' w='99148' x='426' y='889'>
                  <zone-style>
                    <format attr='border-color' value='#000000' />
                    <format attr='border-style' value='none' />
                    <format attr='border-width' value='0' />
                    <format attr='margin' value='4' />
                    <format attr='padding' value='0' />
                  </zone-style>
                </zone>
                <zone _.fcp.SetMembershipControl.false...type='text' _.fcp.SetMembershipControl.true...type-v2='text' forceUpdate='true' h='80000' id='9' w='83564' x='10106' y='19667'>
                  <formatted-text>
                    <run bold='true' fontalignment='1' fontcolor='#f28e2b' fontname='Tableau Semibold' fontsize='28' underline='true'>Task 6 - Timeline Analysis : Covid 19</run>
                    <run fontalignment='1'>Æ&#10;&#10;&#10;</run>
                    <run>Æ&#10;</run>
                    <run bold='true' fontcolor='#f1ce63' fontname='Times New Roman' fontsize='28'>Objective</run>
                    <run fontcolor='#c0c0c0' fontname='Times New Roman' fontsize='28'> - </run>
                    <run>Æ&#10;&#10;</run>
                    <run fontcolor='#c0c0c0' fontname='Times New Roman' fontsize='28'>Use animation, timeline and annotations to create attractive and interactive dashboard showing spread of Covid 19 cases in your country .</run>
                    <run>Æ&#10;&#10;&#10;&#10;</run>
                    <run fontalignment='1'>Æ&#10;</run>
                    <run bold='true' fontalignment='1' fontcolor='#8cd17d' fontname='Tableau Semibold' fontsize='28'>GRIP@ THE SPARKS FOUNDATION</run>
                  </formatted-text>
                  <zone-style>
                    <format attr='border-color' value='#000000' />
                    <format attr='border-style' value='none' />
                    <format attr='border-width' value='0' />
                    <format attr='margin' value='4' />
                    <format attr='padding' value='0' />
                  </zone-style>
                </zone>
                <zone _.fcp.SetMembershipControl.false...type='bitmap' _.fcp.SetMembershipControl.true...type-v2='bitmap' fixed-size='280' h='31556' id='10' is-centered='0' is-fixed='true' is-scaled='1' param='C:/Users/kriti/Desktop/logo_small.png' w='11862' x='80319' y='64667'>
                  <zone-style>
                    <format attr='border-color' value='#000000' />
                    <format attr='border-style' value='none' />
                    <format attr='border-width' value='0' />
                    <format attr='margin' value='4' />
                    <format attr='padding' value='0' />
                  </zone-style>
                </zone>
              </zone>
              <zone-style>
                <format attr='border-color' value='#000000' />
                <format attr='border-style' value='none' />
                <format attr='border-width' value='0' />
                <format attr='margin' value='8' />
              </zone-style>
            </zone>
          </zones>
        </devicelayout>
      </devicelayouts>
      <simple-id uuid='{1541D5BC-5217-4D76-9E64-8BB5FAED09BA}' />
    </dashboard>
  </dashboards>
  <windows saved-dpi-scale-factor='1.5' source-height='44'>
    <window class='dashboard' name='Introduction'>
      <viewpoints />
      <active id='-1' />
      <simple-id uuid='{6F73FAC9-F688-4CB2-9B5D-6845C9BCE69F}' />
    </window>
    <window class='dashboard' name='Datasheet'>
      <viewpoints />
      <active id='-1' />
      <simple-id uuid='{BA12E576-87EC-486D-A4E3-56327D02E9FE}' />
    </window>
    <window class='worksheet' name='Total Cases'>
      <cards>
        <edge name='left'>
          <strip size='160'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='30'>
            <card type='title' />
          </strip>
        </edge>
        <edge name='right'>
          <strip size='160'>
            <card type='currpage' />
            <card pane-specification-id='0' param='[federated.0bd2dna07rjett15ohm5x19xsxxb].[sum:Confirmed:qk]' type='color' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <current-page>
          <multibucket>
            <bucket>20201007</bucket>
          </multibucket>
        </current-page>
        <highlight>
          <color-one-way>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[:Measure Names]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[none:State/UnionTerritory:nk]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[sum:Confirmed:qk]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[yr:Date:ok]</field>
          </color-one-way>
        </highlight>
      </viewpoint>
      <simple-id uuid='{17318997-0E5B-4EEB-932C-262FB0840411}' />
    </window>
    <window class='worksheet' name='Cure vs Death plot'>
      <cards>
        <edge name='left'>
          <strip size='160'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='30'>
            <card type='title' />
          </strip>
        </edge>
        <edge name='right'>
          <strip size='160'>
            <card type='currpage' />
            <card pane-specification-id='1' param='[federated.0bd2dna07rjett15ohm5x19xsxxb].[sum:Confirmed:qk]' type='color' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <current-page>
          <multibucket>
            <bucket>20201007</bucket>
          </multibucket>
        </current-page>
        <zoom type='entire-view' />
        <highlight>
          <color-one-way>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[:Measure Names]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[none:State/UnionTerritory:nk]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[yr:Date:ok]</field>
          </color-one-way>
        </highlight>
      </viewpoint>
      <simple-id uuid='{2B512340-E3A8-4D06-B888-FAD41918D4A7}' />
    </window>
    <window class='worksheet' name='Map cases'>
      <cards>
        <edge name='left'>
          <strip size='160'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='30'>
            <card type='title' />
          </strip>
        </edge>
        <edge name='right'>
          <strip size='160'>
            <card pane-specification-id='0' param='[federated.0bd2dna07rjett15ohm5x19xsxxb].[rank:sum:Confirmed:qk]' type='color' />
            <card type='currpage' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <current-page>
          <multibucket>
            <bucket>20201007</bucket>
          </multibucket>
        </current-page>
        <highlight>
          <color-one-way>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[:Measure Names]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[md:Date:ok]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[none:State/UnionTerritory:nk]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[rank:sum:Confirmed:qk]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[yr:Date:ok]</field>
          </color-one-way>
        </highlight>
      </viewpoint>
      <simple-id uuid='{C190BEB6-251B-4634-A004-C7FB72BD5ABB}' />
    </window>
    <window class='dashboard' maximized='true' name='Dashboard '>
      <viewpoints>
        <viewpoint name='Cure vs Death plot'>
          <current-page>
            <multibucket>
              <bucket>20201006</bucket>
            </multibucket>
          </current-page>
        </viewpoint>
        <viewpoint name='Cured'>
          <current-page>
            <multibucket>
              <bucket>20201006</bucket>
            </multibucket>
          </current-page>
        </viewpoint>
        <viewpoint name='Deceased'>
          <current-page>
            <multibucket>
              <bucket>20201006</bucket>
            </multibucket>
          </current-page>
        </viewpoint>
        <viewpoint name='Map cases'>
          <current-page>
            <multibucket>
              <bucket>20201006</bucket>
            </multibucket>
          </current-page>
          <zoom type='entire-view' />
        </viewpoint>
        <viewpoint name='Number (Total)'>
          <current-page>
            <multibucket>
              <bucket>20201006</bucket>
            </multibucket>
          </current-page>
        </viewpoint>
        <viewpoint name='Total Cases'>
          <current-page>
            <multibucket>
              <bucket>20201006</bucket>
            </multibucket>
          </current-page>
        </viewpoint>
      </viewpoints>
      <active id='66' />
      <simple-id uuid='{A238B349-D6D1-4B18-827B-6ABC3B2C2FA1}' />
    </window>
    <window class='worksheet' name='Cured'>
      <cards>
        <edge name='left'>
          <strip size='160'>
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='2147483647'>
            <card type='title' />
          </strip>
        </edge>
        <edge name='right'>
          <strip size='160'>
            <card type='currpage' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <current-page>
          <multibucket>
            <bucket>20200317</bucket>
          </multibucket>
        </current-page>
        <highlight>
          <color-one-way>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[:Measure Names]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Confirmed:ok]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[md:Date:ok]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[none:State/UnionTerritory:nk]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[sum:Confirmed:qk]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[usr:Calculation_820218120473554946:ok]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[yr:Date:ok]</field>
          </color-one-way>
        </highlight>
      </viewpoint>
      <simple-id uuid='{FB8AAD46-1DD6-4640-9691-26011AE62653}' />
    </window>
    <window class='worksheet' name='Deceased'>
      <cards>
        <edge name='left'>
          <strip size='160'>
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='2147483647'>
            <card type='title' />
          </strip>
        </edge>
        <edge name='right'>
          <strip size='160'>
            <card type='currpage' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <current-page>
          <multibucket>
            <bucket>20200901</bucket>
          </multibucket>
        </current-page>
        <highlight>
          <color-one-way>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[:Measure Names]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Confirmed:ok]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[md:Date:ok]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[none:State/UnionTerritory:nk]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[sum:Confirmed:qk]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[usr:Calculation_820218120473554946:ok]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[yr:Date:ok]</field>
          </color-one-way>
        </highlight>
      </viewpoint>
      <simple-id uuid='{A4A21BEB-4790-417C-AE2F-28067052C4C7}' />
    </window>
    <window class='worksheet' name='Number (Total)'>
      <cards>
        <edge name='left'>
          <strip size='160'>
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='2147483647'>
            <card type='title' />
          </strip>
        </edge>
        <edge name='right'>
          <strip size='160'>
            <card type='currpage' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <current-page>
          <multibucket>
            <bucket>20200424</bucket>
          </multibucket>
        </current-page>
        <highlight>
          <color-one-way>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[:Measure Names]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[max:Confirmed:ok]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[md:Date:ok]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[none:State/UnionTerritory:nk]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[sum:Confirmed:qk]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[usr:Calculation_820218120473554946:ok]</field>
            <field>[federated.0bd2dna07rjett15ohm5x19xsxxb].[yr:Date:ok]</field>
          </color-one-way>
        </highlight>
      </viewpoint>
      <simple-id uuid='{E3583888-526E-4EDF-98F2-65F2DBB5503A}' />
    </window>
  </windows>
  <thumbnails>
    <thumbnail height='192' name='Cure vs Death plot' width='192'>
      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
    </thumbnail>
    <thumbnail height='164' name='Cured' width='164'>
      iVBORw0KGgoAAAANSUhEUgAAAKQAAACkCAYAAAAZtYVBAAAACXBIWXMAABYlAAAWJQFJUiTw
      AAADXUlEQVR4nO3ZPYhcVRzG4fdKqhXBTgthETYEEUERLEaInaDYaCPBQrSIhWKCsgZRQQgp
      lhWZREwTDGhnlS5rr1nsBVPMigTRzkL8SHkt/ApRyDoyzjvkeeDAcJgD/ws/LnfuDOM4joES
      tyx7ALiWIKkiSKocuH5jGIZlzAFJ3CEpI0iqCJIqgqSKIKkiSKoIkiqCpIogqSJIqgiSKoKk
      iiCpIkiqCJIqgqSKIKkiSKoIkiqCpIogqSJIqgiSKoKkiiCpIkiqCJIqgqSKIKkiSKoIkiqC
      pIogqSJIqgiSKoKkiiCpIkiqCJIqgqSKIKkiSKoIkiqCpIogqSJIqgiSKoKkiiCpIkiqCJIq
      gqSKIKkiSKoIkiqCpIogqSJIqgiSKoKkiiCpIkiqCJIqgqSKIKkiSKoIkiqCpIogqSJIqgiS
      KoKkiiCpIkiqCJIqgqSKIKkiyP/s9tx75FQ++epqZtPJvk6sHX4vs3HMOF7M0QVPt2oEObc/
      Qvwmn799T77d+2Gf5+7La9On8+U757O30PlWkyDnNXkj506sZ+fZjdxx6Kl8cPnHfR1b3zyb
      Ez9v5+UL+/v+zebAsgdYWbubmdz/L8+sv5hzr9+arUe2c+W26ULGWnWC/N/cmefOnMzdHz2R
      R79Isr/HzZuOIBfosVfOJ0l23n0+a4+fyskHL+Tokd0lT9VNkAv00/ff/fZh7XC2Tj+Zz169
      Kxd/We5M7QS5QJ9++GaSZLJ9Oc98/VYe+FiNNyLIRVvfzNZLV3PmofdzZdmzrILxOkmsOdZk
      Ohtn08k/7t/YbJxOln8NDct7yAXbPX4wwzD8fT18OnvZyQvDkGE4mON+6yTxYpwygpzTZDrL
      OI5/rkvHNrJx7NI1e/6nnsfw+3PjXxvDsKxZwB2SLoKkiiCpIkiqCJIqgqSKIKkiSKoIkiqC
      pIogqSJIqgiSKoKkiiCpIkiqCJIqgqSKIKkiSKoIkiqCpIogqSJIqgiSKoKkiiCpIkiqCJIq
      gqSKIKkiSKoIkiqCpIogqSJIqgiSKoKkiiCpIkiqCJIqgqSKIKkiSKoIkiqCpIogqSJIqgiS
      KoKkiiCpIkiqCJIqgqSKIKkiSKoIkiqCpIogqSJIqgiSKoKkiiCpIkiqCJIqgqSKIKkiSKr8
      Cv2YPKDOaM14AAAAAElFTkSuQmCC
    </thumbnail>
    <thumbnail height='192' name='Dashboard ' width='192'>
      iVBORw0KGgoAAAANSUhEUgAAAMAAAADACAYAAABS3GwHAAAACXBIWXMAABYlAAAWJQFJUiTw
      AAAgAElEQVR4nOy9d3gc13nv/5myvWIXvRGFJAB2kZREqlJdsiRLtmzJRe6S4xtfX9uJYyvX
      sZM49/4S+97YiW9c4iR2LHfZsiRLVm+UqMLeQYINJHpbYBe72DY7M78/ljPYXewCYBPlmN/n
      wQNgd+bMOWfO+563HwHQuYAL+COFeL47cAEXcD5xgQAu4I8aFwjgAv6oIZ/vDvzhQ2RtRfmM
      iRycmiQhWHnvggZ2DPXxxnjkjJ90c1M7H22uBRQ+9dKrSA4P9zQ3sm9kgFfGJs64fQM+m4MO
      rweA0XiMo1PxM2rv/mWrua7CTywe5r7NO075/gZvgDvra3i1/wS7IrF537eiqp61ToEfd/fS
      6g8QsMhk1DTbxsPmNRcI4Ixh49+vvY6ygk//ffdm7IFm7m2oJNpcy7LfP3fGT6p2eVhfWQWk
      sAKfXLGa+5tqSScaafvdU2hn/IQs7lq8jL9eshCA7f1HefemLWfUXovPz/rKKiaip3f//1yz
      nndUerm7JsCVL7w67/s+v3wVV/ksbBwc4s8uWs8tlV4mosOsevJF85oLBHAO8dNDnTRYNF48
      fuictP/LwwdZaBd5o/fIWVv8AJdVVpl/r6yowgVMncX2TxU/PLgXj9bKbw93zfueKl8VVwc9
      PHl4L0eTSsnrLhDAGSPBql/9gk+tWs9ftjUBKlf99iFOKNDs9fPdzv1k1DQASwLleCWRSSVN
      R6CSGpvII93H6KioY6nHwTM93RyMJQBYWVHDVRVBxhNRHjnRQ1ybaa1WlCTf79yPpmVf8OKT
      23wyo9DgC9DksPL48WMcT6QAuKK2kTVlXnonJ/hdbz+ZIqORZCeXBjyAjq4LyFY3F5c5eXki
      TrXTQ5PLAWgg2rgk6GfbcD+vh7IixbUNzSzzONg8MowgSIDOzrHRvPb9diftHjcAe0Mj+Jxe
      Gh120FU2j4VoLSvnppoqlEyajQMDdMWmiCRi/EvnfhJKdhySKHP7giYWOG0cj4R5fmCAqYL5
      uaqmBgl4vOdE0bdW7/FRb7ddIIBziU8uX80H6qvMbfer665ivceGomlYxKz94f62JfhtNgA+
      1FjDJU+/wM2tS/nOmhWIQrad+xa2cMcLL89o/8NLVnFfUy3J+Dhtjz9jbvO6riMI2Zvvrqvg
      yudf4b4Vl/CVjlbz3g8OHOOeVzfPIIJlFVV4RdAyCfZNiazw2VlfWcXLE93c3NzO3y5biEEc
      ggDqkjau/t2jLGvo4HtrVyDktZZlBrmw2jz84tprEYG/ePVZrm1fxy0VXrpGevjigT4eumo9
      tpN9//IqjQ88+zgfOjmuYyO9XPPSa3zzyuu4szpgtrl3sJvbXnkzfxxlZaCl2DleXO56T9ty
      Pt/acMEKdD6gqgrhjAqAzyIxnMxytgqPBx8Sf7ZsCaIA/9m5i2PJDC2Bat7bUDVbkwXtZxhJ
      ZXeFRrcH2eLis20tAPzjru1MarC2toXryz0z7jXEn+MTIbaGs4r1ZVUznz2YyCrGkmSjzmHj
      npZWBGAkFmZHuLSiOhIZYWc0O953NLdzddALwPP9fdzSuACbINAzMcxnNm/hB/t381q4QAG3
      ebj95OL/3p7t/NOBLv5h374Zz6lxuEgl44zMIRteIIDzgJ3Dvbw0mrUKDUdG+d7RvuwXoojF
      5qbVnt2YL69pICBlueFir2/e7feMD/GzviHz/xqPD+/J7eTGhkYsJz9v9c1sc/3JxT6SVlCU
      rOi2tLwSbx5rT/P3uw/k3dfocgLwxsAJHurpn6V3Ok/1Zcd7dV0DThFA47n+QQ6Gs3PS6K/k
      ky2N7AyFZt6ejnM4nu3Xh9uXUitrHIolZ1xmkyXiJ0XP2XBBBDrP0NHR9Rz5VdPIAFbgSHic
      J/oHAOgaH6cq4D2tZyjaNBvcHxrl+cEscewq4NQWq4eL/dmFvK6uhXUnP5csLi4JuGd9RkbX
      AQFBEJAEYdZrn+7r48sdrYgnrxuNjLJrKs3Ow3txixr3L1rI8opqvntlBe988tH8m/UMH3/5
      Rb64YgXvqKvh7kUdNNgk3vfG9rzL0qqG02adtR9wYQd4+0GJseekiBDLKNy1qIPPL1uOVStt
      yZgLQ5MTDCpZIogqKvctWc7nly4lmcoXL1ZVVOIUAHR2jw3zxsgo6ZO0mWsZKoZDk5MAXF67
      gPc21s56be/4EJ3x6fE839+PDqytbeLmcjff78pazQRRwm+ZyaO/sPIijocGeGk0q3yXWW0z
      xxyfwmZ3UT3HCr+wA5wlbBvq5VtKFNAJZ8V7nu/pZjg8QjKdNSL+5vAB3rRK9E2OExPHOR5y
      EEtG2TWp8K19CUBlCp2/2/YmGyqycm7f4QNoapqnhsMs0fpzroONfceJxkJklKzl6InuQxwc
      sTExNUlXGr6VCIOaAi3FFzdvZrU/y8X/vXMv8dQU22P5IoKiJPjWvr2Ayr/tP8AU8KG2pQRl
      gb5YgiPJ6ed3RUInr4W+pML39+7iSFXQbOulXsy5KJwH0PjGzm2s8mX789yJHgA8os7WiSiV
      luzOcGCklzfDcT6Q08cyd5Bbaipx1GUJUtc1fnTk8Iz30RkOQ2MVy8rcDIVK6yQCF6JBL+Bt
      iA+1NPHIiRPEVN007yaUFLvDEcodbm6sq6PCKvHmUD+bi3jZGwK1vHrD1fyicwd/ubfLbMPw
      BBtm0AsEcAH/RSHw85tuZ6Utw2VPPEWkiB8FcnQAd1kll6xebn7R2NpOe2tj3sXBYCDv/7La
      Zspmil95aF++msaachCtXHLJWmQBfOU15rOaFy+lpnz+Fo4LuID5Qefvd+3gR4ePYjpUiuDk
      DiDyrnffznPPv0RichLfgpVcXJumR2/EOrgVW/0K0vEwN914A4/++hc4go34rRl6Ul4urVQ5
      cLyHiYyDtsYAL715gCvXdnDkwG7GFSd+OcHlG24knMiw7bVXufySFXSdGCCk+rl8oZf0ZB+u
      mnZ+8+uH37q5uYALOImTO0CAloU13Hj7XSyocNDU3sjeLQc4sHUvi6+5FVf8GLt27qLzQCdd
      x6LUBnR6FS/tFRKbN71EbWM712/YgOpp4eor11LnTNIzHCE2Pkjzyis4cXgfkq4QGh9FFx2E
      4xo3rKzk4KhI79FOEicdQRdwAW81TlqBxujumULTQVV19m/eyd13v5spXLzx1LNcde1VrEhZ
      Eaxu2lsDuMsXsrZc59CRflZfvgGFJCf6+tCTk+zpj5KSewGoW7qBVfU2tk5IjEwkuOWWdxAZ
      6+Ge976bnZs3ERns46Zr34uSvkAAF3B+cEEJvoA/alxwhF3AHzUuEMAF/FFDrq+v55577skL
      oTWgqioWiwVN0xAEAVVVkSTJvE5V1bx7NE1DkiREUSSTySBJEolEAovFQiqVQpazKkcqlcLp
      dJJOp8327XY7iUQCVVWxWq3IsowgZGNLNE1DURSsVmt+3MwFzAlVVUmn08iyjMVimfuGecJY
      E4VrphTi8Tgul2vG+yv2Pnt7ezly5MhZ6edcENavX68/+uijJBIJHA6H2SFRFIlGo9hsNmw2
      G5qmkUqlkCSJTCaDIAiIomguasgubJvNRigUQtd1HA4HU1NTpFIpkskkZWXZxMFwOIzH48Fi
      sTAwMEBFRQWSJDE2NoYkSVRXV+Pz+ZAkCcC8rqqqCkUpHhNj9EfXdbSc4C/j87crcvt7Lvo6
      OTmJw+EwGcrZgq7rjI2NYTuZyyAIAh6PB0VRiMVi+P1+83maphGJRPB6veb/drsdVVXJZDIz
      iOC1117jrrvuOgu9LK3iCoKArutZK1Aqlcpb/AbKysqYmJhAkiSTa+u6nrcLGA3puo7NZiMS
      iVBTU2PuDoIg0NDQQCaTYWJigoqKCurq6sxnVFdXm3/X1tbmtWdAURRsNhuqqpYcqnH92XzJ
      bwVyGc656LvdbicWi6GqKuXl5WetXUEQqKioMP/XNI2JiQlsNhtlZWWMj4/j9/tJpVIoimKO
      zRivxWJBluWSDG02LF6+hsuXL+BHDz3Pxz58B0Imww8f/AUgc+/HPowsZNj4+n4uaasmoys8
      /LtnCTav4ObVjSiqxkBMwGsViY11Z3UAWZZRVTVv0Rkc3+/3E41GTVHEuKaQWCwWC6Ojo3g8
      HtLpNKqqIoqiyd10XaesrAxN0/J+jMVu/OQ+w4AoiubuM9siyV1MfygQBGHOcZ0JrFYrZWVl
      Jqc+VxBFkbKyMpzObDh1WVkZsVg2CM3lcuHx5CffRKNR8/tTxaG92xkYncTduJjubS+wfyJB
      JYC7kWj3Nl7bP8F7r6rnocd+j6Jn+7NkeQtPPPwEadVCmVvmyScfx1+1MEsAxWRDg9OfOHEC
      X07iRC53Nri1Ib4YoowBTdOIxWKEQqE8UelUYTxjNi6ZK4/mihJv9x3h7d6/04UgCHi93nNC
      eKIoZfXLkQHKGxdRa7cw5QkQFCPYyxtpqbWzsTPGyuYarFaorq2jv2ecjvYGLFaJjC5TVdWA
      mhzLikCGuGIsGmPBhcNhWlpaiMfj2Gw2cxcwBmgQgqZp5kBzubeu67S0tDA4OHhGA9Z1Hbvd
      Tjwex2q15u0sudcYu45BDLnE+McOw8hxPo0IhaLtXFixYgUAe/bsyfu8tX0ZkWiMWk+aN/b1
      Iyb309rWxtHdb/LSG/twi0mO9Q7RsWI1zz31JEtXreX111/BsmwVXc88STgJa1a189Rzm6bz
      AQq5azqdxul0kkgkZshvkN01otFo3uKXJClPTldVFUVRkCRpxoItRLFn5CKZTFJZWZmngOe2
      aVglilmz/phg7LSFIq3b7SYcDmOxWEwx5a1ALtGdKgE2NjYWJYLDnbuZzgAYA6B3KPt7qv84
      Iye/ObAnW4Tr9ddfB6Br3y7zrm3bsn+LADabDat1On3MYrGQSCSw2+15ooUoiqblJxQK4XA4
      8Pl8JJPJkia23IU9GwcIh8OEQiEmJiYQRdEkpmQyiSiKBINB+vr68napwufM9YxSMHQP4+cP
      GbIsY7fbZ+x+oiji8/nQNI3Jk9lb5wOnypwaGxv56Ec/yjXXXHNO+iMDhEIhUqmUab0xuEgu
      5cqyTF9fH263m/LyclPEUBQFi8Uyg/sbMAgoV1wyXo5hak0kElRWViJJEr29vYTDYRRFQZZl
      RFGkv78/T/TKbbeYKFRoo55r0k+HaN6uSCZnJojnwu12k0gkzPd2rpHLPHPfS6GoXAzHjh3j
      hRdeAGB4ePic9E8GCAQCiKLI6OgoFouFSCRiLiyLxWIuyObmZmKxGKOjo3mmLWOgxQaSTCZx
      OBzm/wYHF0WRUCiEx+PB4/GYz3O73TidTvPl9PX1mQRmiEDG84x2comg2MQWEkIhQRT23SDk
      XC5abMf5Q4XdbmdycjLPuFEMp+rsKoVchqdpmrkGiln8ctF9omd64WulTeBnAlMJ1jSNYDCI
      rusmMSSTSdOuD1lvniRJ+Hw+FEUxbbiyLJte3UIY3NWQ20VRZHx8HF3XsVgspv5g7DoGMei6
      zvETx/k///KP7IkdpN3dii/goyXYxD133W061XJfUKnJLDTdFu4OuU4047PC+wuda+eTAArH
      U8zsmzsXhX2Nx+MmI5nrOYZB5Gyg0DBRzJeUi7aVl/DlL36WZ3/3GNdfu5577r1/zmeIkoyu
      ZtARsNttOTvi9P+iKGGRRVJpJUsAhaZNTdOoqKhgfHycuro6FEXJm/R0ujCZWilp7rLb7YRC
      IZxOJ6qqMjQ0RHV1NdFolFQqxcjISB4X/8wX/gdDcoil9e3sih4g0FFJmVhFX3yCYWeMg2ov
      gz8c4i8//SXTeZe7G8wHuURZSAilcL4tKLkoXCyzOQgNCIJAJpMhHo/jcDgIBAJz3vNWWtGK
      MbFdr7/ID37WwlXt1UyMjpS61YTk8HLvfX/Caz/+P9Suuw05k0JLDPPyG7u57NqbcZBGSE/i
      rWsjowvsf3PjtBUo14yo6zqZTAa73U4qNR2rbyyCTCaTt+BnW3hGPNHY2Jj52djYGF6vF683
      W8bv77/zDQ70d5HQkjgqHaQSGXobxwkyXYrD4szuLqIk8kLfJl54YBO3LLyOB/7bX5iOpPnK
      8rnEPNv1hcTxdiGA0+mLruskEgncbvcMc/b52tGMdWMQcLEx7d/xJmvrr+C3m7fO2Z6amGTT
      5p0IgM8h8vhjz/LO2+8EdhN023j8d09x5+13oCSjPL6xk0++/9bpaFBjMcRiMVKplMnlI5EI
      iqKY3l2YuaVaLJaiLm3jRfl8PjweD6qqEgwGKS8vR5ZlNE1j7769PNf7CuHWFKlFAuH2NBUX
      zV5XpnxFDeUra3g1tY2f/OKnec8zxKy5fgwUeqULPyscz/kWf3L7kbuTAab1rJTD0PClpNPp
      PI47lyx+LlEoqhX2+4Mf+wi9AyNcd+MNc7YliBIupxOXy0Vak1iwYCHp+AiNjY0kMrBgQTOZ
      VBirzcGqFYvZ8sqrSA0NDX9zzz335HXIUDqNzuRaeYzgJSN8wuh0JpPJm3jjc4vFwsjICPF4
      nNra7MI2FKGe3h4+8vU/wb+i4rQWleywsHNkHztf2EbQHciLMZp1oubJ0Yu9kFwiMa4510gm
      k0xNTZFIJEin0yZDMsJVFEUxo28L9ZzcMUqSZO7qNptthsHgrSJuw0eRq3fl7sa9vb089FC2
      qO7o6ARLlyxh68ZnONYzMGu7NoeXao+M6HDz2uubqa8r583N+2hra+LVV16job6aN97cSnfv
      AHZlgs5DR7LRoI888giQleWNcORCp1iuyGNwECOYyQhTNiYxN4ozFArhdrvNiFKDaH7225/z
      n1t+iadjbll0Pkh2RfnCDZ/mhutvOC3xoJQ4VIoA4NwEsGmaRjQaNR2IkiRhtVqx2+0l7zEU
      2ng8W+nNYrFgt9vRdZ3h4WFzxzXGEw6H8fv9RTn/fHWiU0HhMwzmYeh+hXOfGw1658f+O2r3
      FrYd6GZwOL/U+tmAqQQb8n8pR5ORCwDkOc1yJyzXxi9JkmnmlGU5L+xVkiR2Ht5z1hY/gG2x
      m29s+S4j4VE++J4PzIu7G79TqRRWq3WG9xSKy6W5YSNnG5FIBJ/Pd0rtG5zU5XIhCAIjIyNM
      Tk5is9morq4mkUiYHv1UKpXHeQuRy5Fz+3CqxDAfp2SxxV+IYwf2smpxOzdU1fLgrx4ted3p
      wiQARVFwOBxFHUuFO0IurFarOamGwgtZgnE6nYyNjVFdXW3alOHkokukSMdSaEpWr7D5HWfE
      cQRBwB50cOT40VnNooIgkEgk+OZ3v8W2wd24nC6O9R/nE1fcy30f/8R59QQbpuT5LP5Slh+D
      CXk8HnPXtdlsOBzZ+fV4PDPMurOh0Pxb7LeBYov+TJ2MTreX8vJyli9cee4IwMgYyqV6Q5wx
      5MVSMOTPwheXSqWw2+3U1dUxOjpquuEFIZtZ9nef+2tefuVlNE2nr7+XZyZfw+ZzlHzOfCBa
      JDald3DHl+5mVeVS7rzunaxcsRLIvqw9e/fwqyd/zZ6xA2hNMvISK1EUKhbU8dPOh7n6yFUs
      XrR4XmZFA4bhwFhg8xGLDDGnUMyQJAm3e/YqzMYzS0EQBDMUOTcJJtepdSpEXiinFz5/NmZz
      Njzsk+Nj9PbaWbGk5YzaKQUZwOl0kkwmZ3h256MoGltvMpnEarWSTCZNzmP8JBIJgsGgaVLN
      ZDJ4PB5uv/V2IBsHNPiDEbZH9yM5LNgDp78bOKvd6NWwXe3ipf/3RR7/5m/QNI3f/O5hHtv6
      JOJFTsQKR34ytACetjI+/f0/p0mq4+N3fRRNVVm/bv2s49d1nVAoRFlZGYlEgkwmg8PhKMkw
      DOuapml4vV5zjFNTU7hcrjnHNh+xAqYXbe7ih9nl+mJEYTjBChd5rqI93z7NB4bz1ZAiKpqW
      EpBibNmyBUGf23F3OpABEolEnpxuDCydThd9MfF43OQuhghkxO1ommZu5YZoZXB9Y6IKt3iv
      18v/+uLfsnfvXn72219w2DuAYDkzJ4wgCCSEJO/+q/eTIo2jwYN9VekoSEEUsHd46R4b4oEH
      /5qUluYbmb/l0ksvRZIk4vG4GUVpLIhQKITf7zc5t6ZphMNhM4DPcP6l02kzT9pIC8zFfBY/
      zJ+jGo7LXCI4nbYM3dBAoa/lbJpORVFkYmKCtrY2Bgay1p6G9jUs0Pfz2vZ+PvPZz/DQbx45
      a88znwvTnMFInDZ+F2YqKYpiUqjdbjcXucEpdD0bt28QRzqdNsWrUnJtrllx1apVqHadTHJm
      nmguBIq/VK99OutIECXaNizBtSrAgksX4gi65rWrOMpdeFYFuaRyFVdeeSXpdNqMnoxEIoyP
      jxOJRAiHw3i93rxEH1EUCQQC+Hw+nE4n8Xjc1IWsVmvRxV8KxRbobIs5V6GMRqP4fL48/8Dp
      WqxyOfy59hcU+l52PP8QtpYreOCBL/Hswz87o7arG1v5xPuz5v7rbnknd939PoIeb3YHyLXq
      5MKI489kMmiahsViMUOlDRgOsFz53uAaoihis2XjL4w4/kLkbqeqqvLVP/2fvLDxRX74woNk
      qkWsmoBc7865V2Z1fRvb+/YT8FRTYbfSNdpDQ7CF5RW1vHhsD4vKa+gaPsHC8ga6J4ZoCjYR
      S0/RH+omPo8YmKmBSTZc9F6A046dNxRRA3PF6xT7rlAnm+3a3N9G4YLCrLi3iye7GDRNo6Gh
      gf7+/ul+ZpL88Hv/fFbaH+o5Sm9z9pBAp03gkRd28eG73zv7ARmGxSS3nIVhVTDMpsaOYSz8
      TCZjLhqjLIrh+ComOxbC6/Vy5213sHPgdRZvWEB8MsGjL23GWTPzQDebZKWxeiVW2YmaDjEW
      n8IiW7DZy1lTZ6Ey0IquJpFlG0OjJ+ioamF7/9xn9qrJDEs7lpxzi9B8xJBSka6zLWpJkkgm
      k9jt9llNnucDRpURo0zK5OSk2T+Xy4XL5eLEieJHm54tSKJMeUWAvmPdsxfGMvQCA8Y2aOgK
      RscNGTdX+cu1OXu9XlMBLlS0c30PgiDwxpbX+dq/fpmO61vwV3ipaank5vUXYetPEh/KHnkp
      ihIWUWZhsIYTEyNYZCuiIOG22llavZATYz3oiAyFB3A7/ChKnGgqMa8akLqm06TX0tzcPL/Z
      LJib+crpp6s45ookpdpwOBymQcLA+Q7fMJBOp81+lZIKzgVqFyxCdsosb29l++79dAQUXnjp
      xfwdIFdRhexkGxlfoiiiKIq5G6TTaRKJBJIkmeVSDE5v7BKTk5OUlZWZ4dazWZYkSWL7ju08
      ueMRLr17hfm5IAi0LG0gnVDY23mMcG+Y4WCMBWVV7Bvuxi7qnIiFKPfXMzLQSSSjUuPysGfo
      MAI6gmhF1DOgp+ga6Zl1klRFpeKoi7+8/y9OOxIyV3SZ7eWezuIv5PqzeamNwLczed65gLF2
      gHmFZJ8tDJw4zMCJ6UTK3qPZ3zMIoFAf0HU9j7Pnij5GxTfDWqDrulnxbXh4mEAgkBdAV+hA
      yX0pExPjPLLvpyy7qa3oANrXttC+toWD247yypEDWD35psb+8enFfTydW25jmgtOKaWzpcY7
      R3AlbPzFp/+KRQsXlbyuFHLHN5cFBqZNlbnXzWdXKOaMKnaPy+Uyw1QuoDREmLZPq6o6a76o
      xWIhmUySTqdNE2duGURDaZZlmbq6OiYnJ015tPBFFMachMNhyip9uHyzK51NS+pxJQQyydM/
      NbEYvLh47Ju/pqOj46y0VygSFS7S3O9LiU7FIlUhn/OXat+opXQBs0MG6OnpMW3RLpfLDHbL
      FXlgulIEZH0Bhvxut9vNQDdFUfj617+OLMvmws+NIyoFQRDoTR9n8cWze/zsTht3f/A6nvnl
      JkatGsIsx9/MBYP7ZpIKC91NZz0BpBRHL6aYzscmDzN3z1L3FWM6bzcYwXuqquJwOM5pgbDi
      sGYJwMjLVVXVjBIE8rg75FskjAjQRCJBLBYzvXeZTIbvfOc7CKKIfopWlPZLF3Krfs2sk2AR
      7WBNcvP7r+Sxn7xIKDaFpcU74x6v3c1ksnjlMYGsyfXYY50s6ViCS7Xy13/1V2ck9xeiWO0i
      A/O1LhVb7LP6R3Kuz2Qy8wqrOF8wxmEwVEVRmJqaeov7nM4SQFWVceaqTiqVMhdzbtUHQ/YH
      8mzMfr+fWCxGeXk5qqqaPoINt9/BjqeeZuklazmybycWfzUNlT6iSZ1Q/2Gs/mpqA25iisTw
      8YMg2xjsjqHG08guB+X2aqbSY+iCDbfFxURyCJuljDpnLcci+3G7F/Cx+2/Drrj514efpb65
      nAMjx2mtXEQ42k9r9TIm42McGe2jPlCLmknhtNo4Ehqi3G4jqYukfRX8w6e+xsKFC8/I5Hkq
      Fp1inHu2vAPj+1NVYm02G7FY7G1JBIZfKLdYgtVqzfMvvVWQAdNrayi3uRAEgWQyaSbEGGEO
      xj2Gk2xkZASv15uXLyxZbNisNm6/7UbGkgJHB+M4x7fTuPJS3OVuusd0hCNvsHrtegRB5UhE
      JCDrRAUJSZCodzeRVDVGkqOU22uQBIgo0ZOtizR7F9MZ3kdLeRUeTxPLEan2l7El0odVkhlJ
      QntFEzYpicvfQvdkmFqXC4/NSUvNMn5Z1sno6CgtLWcn0Gq+C7WU+HMqyvBc7RoGitwqDG8X
      OBwOotHojKobbrf7tOuFnhasrulo0MIMIQPGYjc6mVszyPAO+3w+xsfHzTRHt9dHuctOy9r1
      hHsPkqxcxmQkQTyhkAyPU1anEQlPEE9YiIbDVGsaDqeDhtpyUpEoLu9CNDWCItlQtBQZPQOC
      gCgI2EQjMUTjRLSbakct11/bQGdXH6FYjP3pJCvrOphMTpLMKAiClWhyClWYJKVmsJ8cS/9Y
      N53PH6TsM2VnPI8GBze82aUw28I+3UU/GwxHU27gndHf82kWNayGmUxmRigJZPtnVCI51zCf
      nhuvXwyF6ZCGbmDc4/P5iMViKIqC2xfg9eefYSAUY2nHQp586mUyOqQyOkI6w2b2Re0AACAA
      SURBVMj2rSDqpFUBNaEQ2boFhzeAz21hQnw/ztQAstXPQLwHTddRdZVQMolFciERQQXi6WHQ
      FeKaAqJM8xIXobCN8UiabbE9aEgkVZVDKRFdzyBOxlB0HUHPIAkigiAS6KgwnXFnIgLlztts
      bb3Vi85wQkajUdxud94CO99+Ab/fz8jISF6JdciKQqdTMv10YYpAxWzGuXEoRsJMIpEwub9x
      IML4+DhWq9Ws6bNkUTOiKGIYFKuqstRcKpHCgK7r7H7tKOvvWE04PZ73XUaHTGbaRKvp2UlK
      aymUVIxNr+0nFU9xdM8xHCuqzGckzLU40+nSeMNiPvPtL9DoqeO7X/v2rBWsSzmfcr835qXw
      +vO14Awrl8fjIR6Pmw5Ko46TUfD4fCAajRY9r8BqtZJOp8+4oPJ8IcN0knpu8ktuiEI8HjdN
      ncbvVCrF2NgYDoeDsrIy08MnSRIPPvhgXmi0cU9uXmqxiRcEgZ//5mfseHoXy69pw2KbvXRf
      RskwMRxh5+Z9VK2qwC7aWNPQzraXj2KpdGH12knHUqDpWL0zc2plu4y82kfqWBqr1TrrLpAr
      ohTz8s4WmmB8f74gCIKZLplKpczw9Xg8bjov30o9wQinKUV8b2XxXjMcOpPJmNSXK9Maclpu
      MJyxuH0+nykOGSKSEUZtXOtyucxyHXNB13U++N57+dxtX2b8JZV9Lx0ilUgzfGKs6LXP/GIj
      XcePUr260vQHOLx2rrx9KdUOK8mjIWpsFjwp1Uy91LWZC3HQHuKJp38/a9/m4pRnO+zhVJ49
      X+h6Nr3V4XBgsVhwuVy43W7i8TixWMzc3c81EonEvApznQ6cHh8WEQRRZsGChunAeUFiwYJG
      RAFsTg+1VdndR2poaPibD37wg6ayq+u66b01JsOI+4dpRTgWi5m+AwOGwyv3WqNOTS5my0zS
      9WxOwZqVa2nyLqL7zUG2vLaFhZcsmNGGiEjKlsZiKxBdBPBXe2hoq8Rf7SFY5+PY1l6UcIJ4
      zwTYZGJ9EezBLKeR3VZ6d3dz5/XvnHUBFDNNFnpl/xBhtVpN2dv4yWQyTE1NmYaOQuTu+KdK
      oMb6KeWoyy2LciqQHF7e++FPEOt6kzXX30E6kWbVkgUcPd7PNTffTiaVYM3yxSy76BJkfx0+
      Wc/uALnyqrELGGUHCxPic0WlwmAmY1s1oOu6GfmXu6vMB7quU1/fwIff/xFqgnV07+tlqHsk
      byc6sb8Pm2tub6dkkVh2UT2XXreIzGiC+1veT4vUAMBUzyTS7jSffd+nZxWBBEEwwz1yD+Mz
      wsDnk3b4dofzZFEpl8uF0+nE7/fjcDgIh8NEo1EmJydJJpMkk0kmJycRRZFYLHbKBgRDHxkd
      HTXFsLMBNTHJm9v3AmCXNfbt24ndk9U/3VaRffv2YnUGSaWmeG3zXi679pppJTj3xRliTa5C
      l9vJZDJJMBjMc1wYpq1c54bhOygVx1KITCbDiy++mPeZKIosq7uII1uPcGJogJd5k4tvXIFl
      WKBC85BOZbA65yaCQKMfgHUfWEVfdx8N1hq2/e4JLq1bzfvedQ8D/QP09/WXvL+mpobly5cX
      nQ/js9zf5xpzKeVnC4Ig4Pf7zWcacUlGnSKLxcLU1BThcHjehclkWUaSJDNDLh6Pm8GVZwKL
      3UVzYz2kmogmNS6+eD2x8R7a29oJxxUuvvgS4pNDuCpbuPaKVbz8zDNZAigUUYxcYIMAilF4
      LsEYAVu5AzAIwlCAcz8vpXClUinuvffeWQfp93n43I338HJkO8pqAavDAiWOwxQQ0As+dwUc
      PPidH3J8ax8Av6Wb3/7iYSRRRJ0xTgFRBE3Tec973sN3v/vdkv16q8Wf87HLGLtgIYx4sVAo
      RDAYnLUNQyrILc1upI+eKQFoaoZ9m55B0DMM7nmSyooyRkciLFvWyqsvPEVFRZBtI6PItj14
      HBbGw5NZEaiwZLXb7TbzeYstfiPZwgh9yLV9G4RhyIaFEZFzLZT21evwAauu2kDQ7qGizI3F
      auOi5R187P3v4vtf/yrti1oJOHwkh1NYRCtl7haq7Q5EQUQQJCyiBQQrrWXZpJa2iotYHFxO
      rSuIxWLhHV+8jurWaiyyBAg4fVVcd9V6ZIsVq0VGELIJ7e7yOq68uB2b1WK+vPmMpVAMOlXx
      73Rg5GKfL+RW/yuGZDLJ2NiYKToVzoURdlMKa9es4dKrbuKy1UtKXqMqKYaGBrMV5HSVkZEx
      dBT27jsIusboyCg6oKQSjIezJnXTDArTGVqGomuYO+12O+l02lRawuGwmTifm/mVC8MidKoe
      Tre/kquuvpqGS9fwxO4+Glps/I8H/pqrVi5GU1KgpdAFC594z4c5dKKXV+JvIHlsVNjrKXdb
      6Y+PU+dpZGSya7pRLcPg1Aj17hoWl69i79A2Lrv6cjwJnUODUUincThs3HXXu1E1jVAkjj0T
      Ze/hPha1L6e2eQlKpnTtm1wUs/sXKstnE6IomhlgoiiaB5OfD4XcYKSGgmxYB42jcysrK0sS
      iN1uJxKJlNwF3vPBj6InI6iCzus7vnLW+mzmAyQSCSYnJ00zpyiKhMNhRFFkeHiYWCxGPB5n
      cnISj8djEkphtWUobiHJ/W42aGqS1zduZM/BYwBUB72saa1Bz6RIxSdBtCJbrSCK1JUH6Dpw
      iISaon+ym6SmUuWqJqkqOORpu79FtuOS4NDEcXrCB4lqFspdNhwuO36bha0796AIFqqqyknE
      43Tt3YrmDLKgvpwD+7YzMB4t1d2SKOT45yLUAcjT0853/q/D4SAej5tKbiKRMPN/DZ9QKczV
      7wd/8nN++uMf89tf/nxefbE63Ky/ePV033yVXH/D9QTcVhoXdrDhiksRIL8qhKZpJJNJYrEY
      drudmpoaNE0zz+8yEpmLiTZGyqTB9UvJ+cUIIPfa3iMHmQKO7dtDNBFi854Jtu7YxWWrl4Km
      kklNAS40JQlKkttarmdP8igJTSUTH0aW3HgsdsaTk0hiVknvjRwhkpxAECyEEhGUTIq4JHB8
      7z46e8JcuW4lRw/s5sTAKEG3CBYnytQ4hw4dxiKqCKMK5RdfPOekFxvzW2EmnZqaMnfk850E
      kxt9auSJz/esYK/XSyQSKTpP937s4wwd2UvfkX3s2H1gzrZ8Xi+VVXVA9qTIG665gmeefJJb
      broB0Wrn1X2D3HD99dNKsOHlNcxeuZV7YXaRJjdMGqbrghbDbDuAIAikomGsXi+xsVEEO0Tj
      GrKWQlWyL1ZV0qjKNCdp9pbxk5d243Y4CK7WEMUJCt1mkeQEAJqWJhRLIlsldh3cxkQkwqJ1
      NWx9blt2DKFJek/es21bCIAUQDKcZ92aDbkMIXdc55ozZzKZtzTHdj44nUOyrVYrU1NTeZ/d
      fs9HWBB0cmJ/CmWeYxwdHiCeXG7+r2sqqXQSHZl0JkNobJyay9uzBBCJRGbE+Lvd7lmVklxC
      yD07oNCtnvvySyWKG9u40+nkyJEjeff+5Mf/SdvC0hUaAn4fX1x/L3a7jW9v+hVl62Z6GDVV
      Y7hrDEmTcHtcjEfDNK1uYNX1S+m4ZBHv3nAP9917f9HCT/OxcRtjLFZYuHAOLmB2GGE3uXj+
      8d+gxMZ47ZVXuHTdJfNqp6GlneaWZpYsWkBlXTOHe4a59dbb6D26B1/jMt517Qp+99BDWQII
      BoNmNKjxIost/lxbdzHlz+12m98VOs+Ma04FhqPl148/y8fed2fJ62qrKgGospSRVDVEaZoA
      dV1nuHOUtRtWYnVM+wtURWXw2Aguv5Oj7i7+4yf/TmWwkkvXrssz5eUmr5fCnHrNLERkiJ+5
      BcWMNv/YiEbX9bwUXANrrrqRP//zz7BqxUrSE708/9zcbfUeO8gPfnAQsDA6EWF0LMxB45zs
      zm7zOhnIc3rNhkKxKBfzSbw4FQKQZZlXNm6krcbDxbesm9c9H1h3M//y8x8hrvPgbDhZSEuH
      TEzNW/yQ9Q7Xt2W9hK0XNzExNMyAY4J/+u1Grmt7Bxuu2pDXb2NBzmb6LPbZXItYFEWTCHIL
      EpzNxZ9bmtIwYZ+OuFSYonm2IQgCNpttBvPd9PQj/D+/nyqPzODx46fYqsLoWLjkt2YwHEx7
      +mb7yb3eQO7BGLMN7lRw+PBhert2cPGqpfO+R9N1piamuGugkkR3djFpqkawZu6kl7JqH06f
      g47bm3lu6DG2bds245pi9v3Zap7OZ6EYYQXn8vR2WZbxeDymgnoq5d8LkevTKPw5GzAiVwux
      fs0yhidirFl/+Vl5joE8z0muHFtqUKW4f27A3GzXzgf9fX289Ptfc/et153SfX6vh0996CP4
      Dx5CPp4gXWVHskhMjEZOqZ0Fy+v40W9+wFf+5q9IxlPFnMwAPPDAA9x00015n50rc+eZIJPJ
      mOVsTjfZJNfrb/w/3/VxqijWxm8f+iWuigXs3rzptNq02N1ctnopG1/fTHPbMlqqvLz0yuv5
      5wQXc96UinvPReFWfzr2fwOSJPHYw7/iQ7dfO//RnURf/yCdr2zm1pY6/nfDTWzqPM4TL29i
      yYcuRdf0WUuo+KxlRNITWCQPlUELl99/EUtua2Hr47t4+nsvoan5Y25dvJj+/n7TAPB2huGQ
      Ot3FmSsCziYKFjoBzyYjuOyGO7ElhpDsTTz6zKkTgdfjxO/O6narli5m494BbrrxpumT4ktx
      9vlsb6lUylReTiX0uRQE0UI8kcTlnJ/pUclk2LF7P+Gjx/nkO2+F/uNQt4ArGhYR6BzDM9jM
      K3VRnI3l+C1uRpLDlNuriaVDuKxlpDIR7LIPVZewiHaqbDWE02GcjQFWfP4ilAjYox5Sk+O8
      urWTKy9bQ8DvIpVKmeMrzAQ70zTLs40zWYyl7s1d6LM5P88GXC4HgcrFhHv3ndb9odEREqms
      3qOoKuGJMBVXdMxeHRrmF3Vo1AgqvOZUJiOTyfDys08T2rWV5ImjDC9vxO1yYbXIpFLZgqqN
      DXVFd6TNT7/AIlmmurHWFFf6+gfZv+MYTXuP0bm4jnSlBY8gI0lugjYFi5Amqip4gHJ7FWnd
      Qo1Dpj8ZZSTRi9NahZiOcmjHMMKITnSqj6RczpVr17LlxWdZueE61vl8jIyMYLfbzfTQwnn7
      rwLD+FHI0HIJP5f7n11CEHnx2SepK7Px+yeeOq0WahcsYkHLApYPtxJNZLhzw3Ie+9WvpsOh
      i4k1xZA7Abqu5xXOOhNl6NknHueqo5uprXATdjcx8sYmMprKSyeGuObSS3ACP332Za6++dqT
      53FBJDxJWZkfOZHk4hUnM5CVDHp1Az2PPUVb2Im6vJWjvgxNznqsFh+JaBzBrhFTprDJHiyC
      gKprJDNhFF3CLVlIK9n6SCc2DrDl6YOk0wppJUNGSzMYjrLhhhuRbNlDQMrLy9E0jcHBQRoa
      GsxSJP+VCCBX5Clm5s69DmZWAD+VuSh27Xs++WfYB3dwNAJf/Own+No//tupDoGBE4f5tx+d
      LI578Kj5uakDGJ2dz4EMxveG6HSmlgBRFJk6coBaX9ZK4XfY8TuyzpDJVIbYVJzLFrdQ6/fy
      w9e2cpHThgRUedyEug7xrqWLpxsb7SOWTHLixZ0Epaw3Wh0+yBb6cIaStD5ynIP/fRk1V7YC
      EY6VCE85sOkV/vW//7SoAry3M/v7iquuN8/zDQQCDA0NYbPZ8Hq95jFF/xVQLJyjUOebTUw6
      FSIotoaWtjXRo4RoL4ea5vZT6fqcKCoCFcb6l4IRNVp4z1wonJBIJExgtBd8MxMqWgNeek86
      tspcTpaIcO3i2QtZTcaTODM6nLTM3jlqZcu/HWCJ4MAtuZF/eIid4SSVG1qxe2Ymy+uajjKi
      8/V/+LqZI11s7KtXrzYZgSRJVFRUoKoqQ0NDVFZWvu1CE84ExhyUUoIFQTAPQTcORhkZHaFp
      QVPe/VDaUlZqZ/nGVx/Aac+GVTz861NPlZwNs+oAhbtBIdWrqmo6WU5l8eemFAqCwLO//Bnv
      b6oqen0qo3J4sJeevj4uX7mcyxc1k1FV5Fn8DgG3k7hdzuPel8jTJ8ysTlmJ/PooQx0VRQlA
      VTWafYv48Ps+bL5UY3y5tZEKX6oR7VhTU8Po6CiVlZWEw1knTKGO8IeEQusgZH0LR48dRdM0
      Fi9abOYHS5LEUy88xRObfseEMMGX3/MVli9bPm+DQDHCSEzFSEydvYpxSy66lHqvxLOvbMtP
      iSzspLFYC22/BhdwOp0kEgnzgIz5IJeTCILA0NAQVUf3YG8tnk5X73Nzj8+Nomps2b+PqbSC
      s7KGDUuLnyMAkNF00ooCculgrJaUzKFXjyPLEv6m/Cym2HgMmxAsWuNHVdWiQV653EtRFNxu
      N729vWYMvHGc6tvdZFoKue83Ho/zzf/4R46KR2BKp921hLVLLqa7t5udx3YQC04SuKQMT8zF
      F/7uz3nswd9htcyvUvVb4Uc5uHsrddfeQNmiNdNHJM1lx4f80wYFQTDLpZfaAXI5p0FMuf8f
      7Ozk2W9/gxub5y6DZ5FELm+s5tqWOsZGR8jMspBcVguWqgCIAkjFPbULJBv3PTtJ8P/bzPDe
      /rxdbuTNST70no/kzYkhzhSLDSr0o2iahtVqJRAIIAgCdrsdQRBm7Bp/aDDGsH//fvan9lLW
      5qNstZ/BhX38ovcn7PJvw3q5RLAjO+6+rQMsXLyQr/z9V/LCaEqJP7quMzU1dc53SoOxpRPJ
      aRGoMGKzcOEaf+debxDEXI6RQgz09/Pif/6AlfFR/nRB5anFCIkidj037kiEpoWgKBDqR01l
      eHzjm4z4qrH50kjBIMl9R8DqgGQULTVNOJIgcG3Mxr6vbWfn4k4QQL27A9+kB7vdboo1hpxv
      JHV4PJ6SL9GYQ+M4WeNeu93O2NgYwWBwxrlrc8UZnW8Y6a3RaJRv/8c/s0/fQ/XKaZFVlES8
      tTOPgK1ZWYXmVejb28PExIQZLGmgmHL9VjgWl61eh9vjwp/qnrYCKYpibu3F3N6FMMyfpUx+
      s7nKX/znv+f+5nLEYHG5fy60+F10DQzTUVed/SARheERqKljeHKKqrJGmiZHicQnqaqrRfIH
      SPZMwEhXHgGYE2JxsexkgOCef9gFKY1vHhtAiES57oufY+WaNUiSZO54hfOSu4iNUilGfSRD
      tDTOVR4dHcXtdpvZUgahvZVIJpMzYu6LQRAExifGeeylRxmNjtKbOIF/qY9yx+yJ7wacQSeZ
      VIZUf5qJiYm8ZB0jndbg9sZcxWKxcz4f+3a8yb5snkyWAMbGxhgYGKChocEMhTZCkZuamkxu
      a7xcI/fUeKmF8f+5vwtx+NAhVllUxDMQBRYF/bxyohuXzUqjUV/S6gBdJS1bkWrL6D0+gGwT
      8XcfB8v8a+SvwAE2WH4we1r51j/9EptvvpIbPvIh6hsaSnLvdDrN8ePHqaiowGq1IssyU1NT
      eDweYrGYmbtbXl5u6k3GEbRGW7lbfynfzKksDsMiA/kH0j344IN89atfnVcbwdYA1381e2hJ
      BTNrec6FA7/vovPxg6x/dD2qMj/Ovn79+lN+zulCamho+Jsbb7wRi8XCggULCIVChEIhRFHE
      5/PlKcbG+QGCkC2gZZwZlpvIPNup5Kqq8sz3/olbqz1nRACCINDodbLz6HEU2Up5TR1YRRgd
      wmO10VAdQPJYcDeUM/DmAVzRBNrkJHoiga7OX1kXBIE62UbjsX42PfwIE7UVNC9eVNSiYdS7
      jMVieceTRiLZQLxoNGqWiRSEbMnJRCJBMpkkFAohCIJZuNZ4frH+FDqZSvXdKFymKArJZNJs
      W9M0tm/fzsY3d/POGy+h6/CJknPgrnKz8Jpmgq35HL812MpEYiLvs5bgQiYS41R4G2n21+Oz
      ZtNSU5EUHbe10XRZI6JFRLJJrFy8mr7emSd2XnbZWnp7s4y4r6+vZL/OJkwrUDAYZGhoiEwm
      QyAQwO12I0kSNpttRr2f3BeRGwZtiETFXowoivzmX77F+7w68lkoxCoKApfVV/DIoSM4bVa2
      HDnOhqWLef7FV1mxaCEd9TWMRTW6xsaols+s2KpDlLhBdPP4179NIjTOTR98/wxuLcsyVVVV
      xGIxs3rc8PAwtbW1TE1NUVVVZZ6XZsxhVVWVOZejo6N4PB5CoRBVVVWm7pFKpXjuueeKhiEI
      goAkn+TwSsace1EUCYVCtLe3s3z5cnM3MmqCyrLMshXLsdp8eKwSN37gfob3v4pmcZARnSRV
      gQ23txPo8BIiQ72vlp5QF83BVgbDPSwILqbCGWDn0EFaA02omUnEk0UIfDY3h0YOsLRmFcuc
      day6o42RVJo6bwX7Ow7SUdFKcv8EcVWkviLA0a79rLl4FXu2b6elfQX+6oUE1FHeOKM3Nn/I
      kLVbGxPs9/vznDtz1ZoxEizCExNs/P4/oasZbv3S3+D3+00xKp1Oc+zIYVxH9+NrazhrnU8o
      KpLVxjNvbqHeZePhl1/l3YsbORjLyrfRRJKUqs7h7Zg/bheddH3vp/zn61u4+E8+DugsXbHC
      FAs1Tcurw9/S0oKu63k1MA2dQJZls3yJIAgEAgH6+vpMv4NRjv7QoUPcd999ef2wWK2oqDjr
      y6hYXY3ot9P94E60dL6I8YlPfIJ169aZOQeqqpJKpYjFYrQtbCU+leLila3ExgfYtHU/N954
      NRnRjUVXmaoNUeGsIaBLqKKDxZWL6BneQ38yhT9ygpQGAWcQSdDwOyuYSGdryabjAk1DFXQd
      38bi9avZNdzF0pq1yNYAreWN9I7uRtTL6ehYzGD3USoq/IQm0wQCPkb7j/LMnhAP3L6Y1atX
      81Ygb2kIQvY4JIfDMe8iSwbH2fh//5b72uqIKxl++duHaWpr4+gLTxIIjyAqCouDXq5YXH9W
      O2+3SDhTU3icNq5vzRLWobEw3bEoY+EIw68d4HLrzOSKM0GbzcnCA71suf/zuCxWdlx9Mbd9
      4XNmQGCuj6BQVMoNKMv1Gxg6RHV1tak8J5NJ7HY7ZWVlrL38GsqcMicO7SWuWmhd0sGWvVtY
      /ek7qJFCHIkkaF7SSs/+47g9HtKpFLKYPcAwEokgy7JZzkZVVZwuP4f3PcKu3QfYcPsGxiaH
      kWwS9euXUFvtZUgKocqTRJJhrBYvcmaKE5FDBMs60KN9RJIRFF0go+noqk7f4eOUjaVYdyzC
      ZU0TuMIh/rcvSmgqW54goykkUxF6x7qx9ATpfaObXYcGaa0v51DPCItcfpSMysTgCCRijEaS
      7Nix46y+t1LIiwUyavnP1yxpyPsbn3uWO+qztl+X1cK6nl1YB/ZyXWUZVJ49jl8IqyRxy8J8
      onLIEn5lkitqqnkmpWKRz37de0kQWO/OZpm1vb6Pp975fv49OkLK5ZihpH75y1/m5ptvNuvh
      F3rXc+fakNkNE3Mmk8kWHZMkrIJK/3CI9Vdeh261cstd7yZukWkILkZP9xJuEKiuWIgQnWD5
      ioWEJhIkYjGi0WxNI5fLhaqqRKNREvEIu06WFknUTLHgHTXU3HYD8cpRjjCa7YwGfZF8OXxg
      KptUOzU2hRZVcEYzLByTeZ+3ghqXE6GuCZQ4Pw+Pk1nhNu/vGt4NQOcTB9nz0HQ489GT1U2O
      d+frIZ09Z5dRzgaTzZ9K/HquQnZw/37srz9DZU4ow9LqU7cWnC00+D00+D2omoZe5UId05EE
      AamiHHV0DKmyHC2eRlAT6BYXQipa1DQKIvbVyxHScRL7DxcNihM8ZbisCjeGRHw2lSfGhjmc
      mmIwWMk6NU5veIoXnnqS0EtPY/GXcfXHP2UeCTSblcf4MRLlO3dsBtnNLTddTTgOkmylpr2c
      TiWE1+EjOrgLXdFR0wk6d+7C7RFJ6h6aaypwu92mYy6dThMIBLjrrru4/vrr0TSNh5/7DePH
      QkwoEdyVc1vLtIxG+/4E9ztrKLNbcdXOrOR2V3Udj71xAOeVddNjUnVqymr43mv/WtTRZdQ1
      CofDDAwM8MYbb40WYBKA4QeYD/c3Fn9X535Gfvpdbi0Rx3M+IYkiN121hEdf2sv6CQlnx2KS
      o2PYlrShp63YPAkUzYekjjG1twfbwiaUY0eQF7SiR0ZIdg0jihnSCQvOVR0ILi+pI8ewNjWi
      Dg+gyW5szU1kju3HuriDqydGuVK3IXhsPDsywU0Lq9AGxnh061buuWEJbi3Mq3/75zxl8/Ch
      //svRaNuDetQ7lkNAMHqBloaKtm48Q2s7gC6AP2NYZqaq3lu/yu4q4Ice3k7saEoiUya/QeO
      oOpWWhuux+l0moecGPqHw+GgurqaRCLBVz77VWRZ5oH/9QDRzATiLDumpmos2xbl8xWtSEWy
      6zRdZ9PwCP3pJNVuG709k6iDGi7BzdK6ZWy0vcjug7u585Y7izJbI6p2tgpyZxsmAVgslrza
      QLPBIJKd//bPfKJtfiWxzwfcNiuqLJDUNaY1AR1lZAS9px/VuwBh7DCCNQgq2Ba1IHhcRLf0
      ADYsTc0I9hGUkSnk9ABaSgd0bIsXkolEie86iKO9GYtXhto2kkeHES0CN7i8qLv2YWlZynq7
      n1d7hrmjrZHrGqtJdPczPj5OTU2N6fHMJQK73W6aTAVBwGKxEI+Msi8yChYn6VQSO7B0Wz9T
      3aOsioE41s327kFwOvCVlZFMaeh6AlvBmW6GjmIU0TJ8PoqiMCXHEKTse1UVFV3Tkaz5h1+I
      u0N8xtNSdPFPKQo/7e/l+VUWnEE3E11hPrf6s1x6yaXTmYLfh5/9/qfcddtdRQmgWNDluUbe
      DpB7JOpc2LdvL2s8p1DOWnIitDZBOoV+fDohAZcHporU3gzUQHgQoaoRfXCmzXg+iKbS9CUT
      HE/GWHH0GNVXLKcOBX0ijOWidjJdQ9iXLiETUwEdXcmgDo2cvFsnffgwid1dSLXN6JkJpGA9
      ogS6ooDswrE8gDpwHMFSg3riGGoC5Io6xKmxrIKoKPhlC/uGokwsSFFmePXU6wAAIABJREFU
      t3FZTTnPfe1LSNe8g+vvfDcOh4OJiXE8Hq+pDOdWoWtubmb37t1541JVlYc+9nHuiZ1cROVQ
      6wrS+qf/jQUdHVRXVSGcZGTJZJJDBzqxSBLty1cgyzLJZNI0yVosFl594Xk8URd9+45QmxBp
      j0rUajJPuxPIGnhECVHT+YBUgc2ZH4U7lVb4eX8vj8fG8N3WjMsqMb45zOfe+WesXb2WUChk
      6pV/8uE/4VMf+VTJMHGjushbmUoqrF+/Xn/44YdRVXXGaTClIEkSO7dvJ/PQv3JVU+38nFqW
      MoSgBI4q9IGjCNWNkEmAZEUfHkaoroVUDNzlEBuDilaEyHF0WwCUFEyNgeQGrwsmE2AXIZNG
      7ytNHJuO9hFPprlsYT3DsTjPnBimPVjOeNcAqpKhcVyhUp5flOKZIKZm+L06zqevXY7rZKn1
      zlCYJxIiZfUNBE90Id56D1ff8g4guwsYYdfFYq1EUeThf/pnbntzM1LO3G+bihHWNEJWK2PL
      lrJg6RJ6D3ZyTWwQj93KprSMy1+GMtwPooQtk0a2WrnMZyeVUal02fHZp61YOlDqzeq6Tud4
      mB9PjdB1cRkTR8aoafbh7vbxFx/7ItXV1WZEwanEeqXTaXbv3s273vWu+U/wGcAkAEPmnI/5
      03Cx7961kz2/ehA5FmZduZellbPU37GUIV60DKbCaP2jCH4PgsMB/z977x0n11nd/79vmV63
      96qt6r3bcpE7YAPGwXRCSQKEkJAfaUBCCyHJNyQQILRQgsHYxjSDm9xlyZas3nclbe87O73d
      ueX3x+wdzTbtqtiWnXxeL720M/PMnTt3nvPcc87zOZ+TUdFDYQSXE8FmwYilwC6BZsUYOIZQ
      2YTR34tQXQ1WF4LPizE0ijHaiVDZiNF79rznmtE0dvWN4CwoZGVtJfbJTT1N13nwuf0sPTQ+
      ZRJdbmQMnUNaHAosNNYUsKr83K6qYZxr3/GDwTAOTSVkd+IsLqXlljfRvnwFv77v52y59jqq
      a2pyit0ul4t//vCHWdfTS4PDSfUsuqVpXWe3rHDH+rZL2nWfDaFUmsfGR/lhnYalxJmdO0cV
      3rHlbVx/zfbcpDf3Ry4EhmGwe/du7rrrrst6znMhN9vNAGwuA8hfhUyLXr5iJStXZTcsfvY3
      n+C8Ela6gt5xEGyFYJkMAGMRsDph8pZoxKOABVQVYyKIUFmHkYiCoUE8DpINIx7BSEZBB+M8
      RRKGYbC7d5ioILG2tZlSz9QMhySKbF+7hN+e2sHG9Mt3FxjKpAn4DO5YXEWpa+pEFQQht8L+
      YaUvb6WMsfd/vsFDaZ31TokfHTtKud+HNRzAPdTLgMXJUiXK6WSS7ycT/LHXTyydpshiYdVk
      5xUR8Ljsl33yA/znaC/PVwjYSrOfpas621uu4cbrb5qSUr+Yji/mPtQrhRkbYXOVpeVjeppO
      FEUEdR4OtxaHEEDW3zfGAMmGUFUJoRGM0MjMz4md03k2AiMQmDYmMMpsCMSTvDAUYG1bM5X+
      mTRdE9FUCs/LXKRVa3UQjGgMR5MzDCAf06/5utICTEH2T6VjOJQUFpcITdWous7OriQHPG6+
      8p3vcO83v0X01ElCIyOsnOy79UBojA9tnF/S/ULx0liAPQ1WbKXn6CW6puNwTmW12mw2FEW5
      oK41Npstx516pSDCudJHq9U6p778dB5Kfr765MmTLJYuYiZpaYzervnHXQCOjU7QlYE3blh9
      3skPcPTgGZboL38MIFlEil15E8TtBacTEECWs4/PA6/NisUMalWNhw53caA7wPu+8x1qa2v5
      s8/9A7f91V/R4XDww4F+DkejfO1MF+OJFLphEE6l6Y1k75b5k1TTdQ6PBPhKdycP9fZz/5nu
      82ZgDMPgQTWIWDqVWyXbZPae3DdlxV+IVuxsx89vz/tKYIp5znfS+bnp/JP0+/2cUl7dUj9N
      19nZP0phUTEb6uZPzY5EYiQ7hoFLa8y2ECzFyaFdfewtkLl6eRPFq1sxEgbG2BlARKxsxoiN
      o/d2IVYvwoiMYagGgseDMdg35Vi9kTiFCZ2OJUsoKCjI/Q5HjhzhTE8vnw2HkC02HDaJJ7oG
      6CyXOOmHtE2nZFCl0l3E+mCalYWFPDY2wm/scTzbmjiixLjjxdmJjABjiSRfP3KSvraZm2WR
      /jAfu/EDM7I7F0rdnqsn8cuJKbP9QhWezfxycXExyY038NvOPn5+optY+pXbyDBxcGicJYsa
      WbmAyQ/w3IvHaFbm715/OdCtJpmwaugJlceP9YHDheB1YSQ1hAIfhp5BjyoIfi9IIlLrEsTG
      xZCY6Q60FHpJF9pY2Xmahz74IbrPnMnl9t/xvj+nqcLHio1XcddbbuVF3Yp63WLkliKWbd1M
      ya0rcN66keeub+fvlQGO3LacxbeupbAoS18WG9p4JpnE8PgBETw+hJpFxF0uvhgf4KXtJURa
      z3V3jI9OxmARnabGphkTfqFBsNVqxel0EgqFKC0tfUXFA6bcAUwGoonZ6BGzWbWu62y//c2E
      tl3L0SNH6Nv5K9pLF1Y1dLngsVmIptKU+TxTznP6inawq5/T+zo52D1AQrey0eGbcazLiQE9
      jW9pAdsqi0mpGqLgwIgGMSIq4qS/TjoFmoZQWAaoGBkVEhGM0EzFaFXXiaJTKIncrhvc+0//
      xOHrr2ciEODskW7qFy8HSWQ8qrBo5Upk0ceqyhKGQmco9TcgCDBsRGi7bS1RzUZ7cRuHx7ow
      rDKH13qps9bR9cIg7yutQVAjIEq8WFNDj6eLdG8QLRAnEUkjWUSUaBolnOLNLW/A7/dPmSvm
      pupCcvrJZJJQKERBQQGZTOYV3QeYUhOcH7Ccr9hiLiPw+XyUlZcTTL3y8h+LCv3sGhpmNBKl
      0O2ic2gUn9PO1W1NuTEZTeP5R1/CIUmEytwcGY6yzjA4m0nSbM36teOqQlexFTGtsSZ58XeI
      qKbSYUlT31rEysosN8ouS0AGo38Q9Ax6KAwWCRBB09DDQwjeAvT+PphlEjw6MMpEMMpGxYbT
      ZUUSBO4ORxn46b38YHQYV00Thr8OdeAlcLUgVBXi8BlEUgm8jiK8NifBVBJFy2CIbqocNqJK
      ChGwOcrxSyqKVWR38iy3rb6DkhOnEeUMpVGDdCCB32ulrKUYTdURBBg7HeDuRe/jxu03znB/
      zDriuWASA61WKyMjI5SXl5NIJC76el8scjPeZILm42KCkdbWVh5sWEFbtIdC50zNnZcLkiiw
      tbKYmJJhPBpisdvKsXB82hgRW2UBQlrlE9tW8vVHnuOJoSBPyyneomjIBqhr63j71Wt4dO9R
      xnf1ENU1ougst7o4oSWJ6RqNoo0iaW5fNaKp9NWI3NrUNDnp82FgTIyde5iZ5jeHAjOOp+k6
      P4vGkd58PT0HTrF1Txc2USKlafwkFsVZXETlmMDvXnwOXZLQU3EsJ3p5bMczVNcX42gvZdPW
      1Ri9/Tx7bB/h8SinEnupWb4IQVQYGwiiptMs274aXepG8clM9PVQEhlCp5Cf9uxH8qQpXZVV
      75Am+UI2t42eke45aQ3mJt70RTO/bHZoaCjHS3o1IMM5Ily+2zDf5J9LxUDTNG5753vY8Vd/
      wl1Lzq/gdiHoDUWwShI/PNjBH69djN8xU5tHEATOTkQIIFHm97K2ZCpJL6lkkIfC2NI6lX4v
      X3337QyHo9wlisTTChZZosjtRBJFeifCvFAmUl9VxuhLZ3CmBbw3LqGl2M/xI2cZOTPGYm32
      DFJQy9BeUTHL5L84/CYcpeiDb6WotAhfeTGdJ4dYFE7Sm0pS/J53s27TJpx79zLw05/mroNZ
      HaYoCvYhK+EXQvSMj1AkF1DrqgYfCL0CiYRAk6MBA4PU01FcqWH+sW055cls8L2r4yTDqx3U
      Fs90aX2VHpI9M1dtTdNykpH5xUAmTOOIRqNUVla+Kiu/CRnA5/PlmtxNn9hz3cbOJwtitVoJ
      Vy1CN/TLshGj6wY/O3qWAo+L3nCMk2MTrK4sRTV0nNOyBn2RGKvaW6kt9M84ziPPHmB92krK
      0Nmx8xBvum7tnKnSP77lKgzDQNV1hpa2EIjFWVJVjlWWaK8s5YVjZ9j//AnqEsy4G3hFmZ5g
      lAbfworxNd3gmfEgzQ4blS7nFLKZquuE66upmoypCsqLOeaxcd+BI/x2dJTwS3sX9BkALS0t
      3HPPPTmtIlmWiUajWCwWqqur+e4/fp7UoUGKUUAXSakqj4tRbEUlsx4vcCbIuzZeP+MOYDJP
      z9e32GKxEI/HKSiYv3vPywkZyOncmHlYs4jCxGz5/7kgiiKyLCNVN/CLFx7DbZWxWSyEk2ky
      mo5VEllU6GXZBdQMTCRTRJQMb1ncwpr6GkbDEZ4fjxKORLmjZWrBzYryIl443kHNlnUzjLex
      qYqJo6OUylYGu4cZDkUp93uYC4IgYJEkaov81BZNNaiNSxaxurWOHz7wJEo8jctioX1CpVCy
      UCBb6DwTIlFVgl2W6ArHaJw0hunnZDgLeSEwgPZH72f3+ACle06xKREinlEJKxk6InFcN2zC
      ZfUQV6Louk5FYxvhqIF3zzOExxbWWmn9xi2kI+O5WmO73U4gEMDn8+XcFI/Nyp+uX5JbtE6M
      hehe78Exh7yNe8TPsqXLZk1/5pfVzoZQKERdXR2pVOqC1S4uJ6ZQIWbT8smf8Kb2I5CrcDJf
      k2WZcDjMi7t3s3nrVv7n29/ip2/bTrnXhZS3EiiaxhOnujh86BQry4txWGQGIzG21FXOebcZ
      jSd4w8oltFWU5p5TNY379xwinEpPIXA93zuMxTF7Ebx5DqqhszYi8OTuw7zjlovvOWWVZd7z
      1uswDIN9Z/sI/+4whZIFzTA43VzOPW4nFreTdH0VyvA4bw9FiCgqO3WdGy0yewwINCyi6eZN
      VNfWUFNXTKi+iad++SziiiZSLgtlpeVUFFgodJdhRFUOHDzARkOiUbATrK5lwzXtqMkIEwkL
      TlElHunDVtyM1+fiyJNPUL1kKXYhRUK3oydlmpubc0ZQWFiY+03379/P0YM7EVYuIaWq7Oga
      oF9SsXlnX6jGDwX54h/+85zMTlPgypw/s4mtJRKJXAmo+fwrbQgz9qnNopjZqpW+9pUv47Za
      8Mgikq+ATCyCJloQMLAExyhJTHA6lMDt8XDH0mz2RZqmKmeTZW5Z3ISiaXSMTHA2EmU0mmRp
      SpnVrwcocznpHJt6V0ooGZx6BlkUebyzl2XlRYzFkxQ5HVyzetmsxrSyoZrvN57BI1twnxjB
      dxGNnKfDbsleQrfDhiZMcpyAkhVNLH/79tw4TVV56NdPIVSXU7+0iSdPdlHZVEuFz02BqwJd
      iyNIXgqKBeTbt2MvcCJKChbZiaoliacjRFMxkruOUlm4iL8uL6ezqZZuKcmeIZFEMshTOx5j
      243bkfQw+44MU1NZjdcmUVJaTmfvuU6JkiQRj8fx+/0kk0l+97vf8cjQryiss9MbifHDgT5+
      4UljVRTWS6VMh67qLHevoaKiYkrzxOkwF0szvZ5f/1BQUEBfXx/V1dUz9p8udAf5UjDDAEzr
      dDgcuY0ugLGxMVYGe7iuuQ6XzYqmjyN6BARhcgVwewAPWxNJhnb9lhs2LJlT/kQQBGyyzLKq
      UpZWlrDj+BlOB0IsKSvCYZnJHSl0OigSQgQTSQqc2fOyTfqZe/tHcBQWMSraCAgqoUycYCJJ
      hW9mlkYUBD74pm3ohsGhxYO0Vs78cS8WZ4bGqZ40gD41TaZkamwhyTJL3npD7nHzmsW5v1U9
      g6IksNlspJQ49hIPVkkiqWjIk65ERk3R8etdLN7TiXhdPUKhm+buTtpqF9EV7+apwSE0YGio
      H1dBNVs2rqJz57OoGAwODTMyHMIxeUnS6TSqqvKDn/w3zx16mkxJisXXNTPSOcY7f32YSL0H
      0eNEG8oQ6AkiGFBQ588tKhO9Id6/9aZ55d/zJTVNXpC5sOq6js1myynu5W9+xWKXTwl6Psxq
      AAUFBbkv+5v7fk7HjofQMipvqSnBZctG9dIck7vQ6aBwgb29zM+7qqWefX1DnAmEWDpLbCAI
      UOK0E5o0gKdPnKZ/ZBSXJCL4C7i6pWHBnHNBEJAEgdUNF1d4ragqp0YC1Bb6sFtkrJP57uJC
      Hwfd/TREkihb29mYEOntHaaitnzeY0aTWdJfOplNjyrpMAmyK2VgIkAinmDv57/PmzWZeqeL
      9Au7cu+NDb/IQNcZjvVlszZHjpxk5YZiwgNnOHL6BKmTx3JjlyxZQiaTwel08p8/+hqRRaO0
      3F2baywuWWWCtW4snuydUS/zcLQjiKdTpWxzDRPxADFrBLfqpbWldUEbVvmreyaTyQXI8Xg8
      10uhoKAgJycTDAZnpONfTsxK1cv380888CNc6PRMhKlf2fCynITdIuOxWbGf54L2RWJcv3gl
      QnUpa1NpUlVt1CjDtBcVnZv8ogUKCrMEj7GZ7NIcbF4oKQQ1A8MDs48pqYSxwRlPq8XlPLv3
      GCstDlQ1SSqdRhKgrr6BdWvWMBqOUFtShCgIBPecIOJ14T1PoD0XlHSGE7sOUvPTJxnUVD5o
      ceCZhVn5VCjIW7/7XT4wmU1RFCWXffnsP3xhxnhBEPjMZz7NkLeXtopsmlrLaCTCKc4c6Ed2
      52kYiSIWrx3FFiM9mMGhu0mHVHpG+vnkJz8JZLWH2traZnyG+ZuY6haSJOVWeVP7yOPx4HQ6
      SaVSubSpqYn0SmHeBhldgpPQYB/fftPVLwu33MTyqjJe6OpnZ/cgW+srp7wWTqUJZ3Qkiw18
      BXhcbm5Zuw669oO3DNAgY4DdDpoC3kJwF0AsCpFRKCwHRQWPB3o6wGKD8AgUVENlY/YqBENQ
      UAQTw1BUjuBwYCgqeD2QiGaPGR5Ds7hpWrOZxhInldaZblaD/VzKcEtDA/c9vo9Oj401N59f
      79IwDAbP9KGqGuneEZy/ep61aY0Gm4ON5+GHVVttDJ05y+q73pbLvKiqOmsPg3g8jizLPPDg
      b7j9s1cD4JBdBCYmuPdjvyCaylD//rUzqsBGQuP8+PEfT3nupb3ZRuK33nprzgDyg1xTKlJR
      lFwHUavVOsPfz5eR1DQNv98/JyP55cB5ow1RFPmvnz9Ay6q1hJKp8w29LFhXV8lYOsNDJ7tI
      Tu6QDoRjHIkqvHnTGgTACAahrglCo2BzI1hEBJcHrBYYnKQQRMYhkoDoGFQsypZUutwINrcp
      BolQWg3hURAM6D0LLm/2chSUQHgEIxwGf2G2zsFigUQC7A6cqCxVQoQDYzy+/9B5+xT4nA7e
      374E0vOvaEO9w8S+8lOkb/yK6l/t4josNNjmdwWWezyMfuu/cp3mzVV0ehIj3yhq2tew1KjB
      MCSurt3O0NEwXpuT9Ss3sLpsESX+SlbXtSLJTprLG6iweNly1TYaa8qob27n6m1Xs2bNelry
      3EgzdsyXdrFYLDPUr+cLcDVNw+O58DvmxWLecFsURT79r1/lx4fPzDc0i+IqhOrG7Gqb/zFz
      pCbPva8CSRR566p2rmpbxO9P93ImEEIzDA71DWKRpOzqHh4HJQWhYLbAXjeylWTxBJRXgpLM
      TtZ0DDIKyFaYGM9WmSVjoAOZJMZAD4TDEJ/Mo6uZ7PFDY+AqznJ0RgcxRBGS8WxxrKoipRNU
      eZ20+T34NIWx8CwF/XmQJYliZf7UXqhniNW6yLWqyMoL1HJ02208+P3v57IsVqt1BrVg6qaU
      weEX+hh9PsFEvI99v+uj0itytj+AkUqwpKKezlCG1fWLWVdZztBYBItF4obrr6GldRHHB5P4
      jVGaWhYzFwxjagfRhUJV1VevImwu2Gw23vi3X+D7P/gmb63y43fO5AyFkinCaY2KWie2sSFQ
      01BeAwkNxAiCswjDrSH4fRijQYTKIoz+PvAXQyaJUNWEoaUhOEGB086ty1r55cGTFPi8vHPz
      2uwHaUmIAbG8IppY3gSczh622LOujq7DYN57tLz3mNyb8bxYIH8jcGDSQMLn0ogA+473ELfY
      KSuYn026xF/IoRNnqW6owmafPfXaumUFe20WpF/tpGIwSLvdgWuBk+eNbg8/6uubkWUxsy/p
      dDq3spqv79t9lNsbr6enbxTZKiFkXLxl2xZ2nTnChro26gqLiCYTHDp6gKKiRViSEdKan3Q6
      SUpRiCfiWPKEkOdSrjYbiyy0Msx04V4pLOisBEFg9dp1tLb/J7/4wfewHNrF6rJCKrwu9g8F
      OIUNpbyO/v1P8qVVqzEEEaG6ATIZDDEbTGGxItgsYPeANYrR3wHWIgQMcLmz5Y7BidxnuqwW
      bmxvZFf/GEXui1R3zqRg7PK7bv3BMEFDYvuKpQvKPi0tL0PsGmTXRISlW1bOOkaSJBZvWIay
      spVDuw7h/tEO2pwL0zUVBAG9t3fKiutyuQgGg7hcrpzGkKIoWK1Weo/vJRIYp/s/etH+3SCd
      UuiXJfpDj2KrdbLz1Iv47TaGAyEGf7yHZEIlUVnO7kNHyeigZDQOiBpi907e/b73zzrxzUmf
      L/O4UCO44gzAhMvl4t0f/TiBwDs5sHcPe7q7qFt7C+/ZtJkHf3oPb1nfjhFPIhQVY4THwebL
      FnyMBRDI6uQIiQikYqBkQFDAsGeL43Upm8HJM4LxeJKKecoaXw0cGxpn/epVC069RpMp9iXC
      tN+0dd6xVpuVRYsb6agtpmE0jm2Bm0KujDpjIsqynBPtBXK7rm96w225vg7T+ffBaIgz0QgZ
      NYUWT7J2zQbKy+ZO5ZaXl5939Ydz9JgrERd0VoZh0NfXh8fj4bobb2L//v0M9vfz5T98B5tL
      vZQ2VMJYX56M5kT274IKjMAQxOJTJTbT4xiRcabDMAx+8tJRFlVWsnHRyyeueyHoGg9yeGgM
      WZZpqK+n0LMwopthGPzLk0+z6UNvQhAEIqEoiqIQmYhQ31I3JSg88vDzyF4XzeuXYvnk3dzz
      Lz/h/RPKnNo8+fAoCrFYDK937gXDpCd8/etfz2lAmXLpZuB69uxZ3vWtjyM7LEguK3e+/S7u
      vP0tOSPK7wWcT3HINwLDMHIUi1dS5vBicEEGEI1G+dlf/BEDFjf1NdVEj+3n1vZGbl7fev4U
      aXBoysMTw+NkNB2P3Uqlz41t2uogCAJpVUfV9Tk33F5JGIbB8UCYG7dsQpYkrAtczdIZlQMH
      j3LDSJChr99HxGLB1z9GAZBSVSJf+Sj+wnMxRKJ3mLec6Oe53UfR1rdj2bKMvvufp3aWjSHd
      MKZc8zoE+np7WbJ0ae45s0lfPjweT24HFrJGYebhDcOgubkZKaZDGUg2meeO7OauN985pXGd
      qeAGU5sqTidN5jNCL0Qc65XEBRmA0+nEWdPA3xZbKHTaECo3X/AHGobBYxk7I7EkZZ2dvH/j
      8hkGAFDscbKluf6Cj/9y4JmOLsrLq3BeAHdI1TR+8dMH2ZxW8MoWVsVVQAV39s7Rm0mhZlQO
      P/gkviWNSDYLFknCL8u8aSRC6JfP89WBAWJ2LzDVAFKaxvf6+vhATQ12USRjGLS6XDz4zDMs
      X7FiiusxHVardcqmkyAIOByOnN8tSRJCVCM9EkNIGdz0xutm0ONNn95ms3H8+HHq6uoYHx+n
      rq6OdDqd620QiUSwWq0kEglEUcRms+XuILIsX3CG6OXABS2vsixz9999nt8PRWZTC18QeoMR
      Wq66jhJB5V3rluKdJSuSzKj0j4R4aNcRfvPsoVmO8sohraoEDIlldRfmik3E4lRGY3jnuFts
      Fy3YP/ff3PX8cVb854MM//u9LD/Zm1sp/bLM39fWMmZkeHR8jFTeCjyqKDwVnEAUBDoTcf72
      1El0QE+mpqzUTufU5IHZ+GR6DwhTicHM4W9pXsffXP8n3L3sNt506xunxAj5q73ZHyISiWCx
      WOjo6CCRSDAxMcHQ0BDxeJxIJEI8HieRSJDJZAgEAoyNjV0Rkx8uonlQcXEx2z/1Oe7518/x
      9rpiLHM0op4L5V4Xu4cHSTtmb5Snajr/7/tP0jQiowoxTnkU3njV8gu6hY5FYyTSGY6fHeTq
      Fc05/tJs0HQdRQdHZW1WhUG2QGgC7F4wkpzsH2ZxfS02k6Rnd0AqOfl/KrsBN4ufe7ZvELd4
      7kcWy6owgkMYSnYyOSSJjZMdIqvtdt43y7mJgsD6ogLG0wqPBca51l+EJAg8XlqMvd9NTFX5
      wulO2rw+ziQSFDU2YLFYckRGq9Wao63nr/jTMf25v/+rT+P3+9E07bw+vKIo1NXV5bJP5q6v
      yTcyA1+zu6iiKHi93ll3qV8tXFRoXltbyxs/80/84Iuf5n01PqwXUPpnkSQyoSAF1XXc/+IO
      Prx51ZTXdcMgkVQYljTsukh9zMI3vv0orkIna9YtYnnD3LInhmGwY/8pTu7oQAwpuHSR+0Mx
      3nfjBgBOD49zpGuQm9e0Y7fI/GrnYfqPDlK+eDWS5ShOu43lt9zCYDQEI2Os3bQUpy7SXFGf
      3diLRaGqFoYGoKIServAIoOnCLQUpDLg8ZCKhegdinLL5o1ofUPI9XUYmoFQW4YWCKCdnbsz
      43T4LBYUXcfnsPEjr5slN9zA22+5hfG//Vs+29HBWQMK6mr5Um8f781k8Pl8Uyb0bCWJ02Ea
      htmkwlSpnq1htUlzMFd/h8ORe78kSdjtdsrLs1kjkw5hxgyv5AbXQnHRuamSkhLe+bmvcM9n
      /z/e21C0YJ7QkeFxWt5wK42LFrHj4LMzXrdIItfdvIT9+7qJDiWoTjnw9mjQE2XXyb2cvWaM
      whIvVotEJJqk2O9mVX22E8lQMMLZRzqoj0mAg2PWOPUeG88cOc3QSJCxnX14UgL/9cRpsEnY
      JzLU46B0iY3u33QRR+TwmAN9OEOsUMYuRJCaliNYrCDIYJMhEoRYGML2LMXB4wJBBEPMGsnY
      CL0phTJZRvCXIWZ09OGzGPZS9IGTyE3L0Fi4AexKpkne/U7Wbr3arvgYAAAgAElEQVSKP2hq
      yrkOX/35z0mn04RDIXx+P5lMBq/Xe1HBplm7G4lEGBsbQxCEXJnsdGiaNqWVq/nPzPxMh9nw
      49Wq+JoPl5Sc9fv93PQXf8f9//wZ/mABDfAUVeNZw8Ofb72KJx5/nA11U0lvhmEQTSsc2tNN
      e4+IIEzlhFQlLWi/76fPUNEBKwKnBAXHx7dRVeDl54+/RFPs3I/QnnES/3U3I4hYEagXbCBA
      URyIn/v64WP9NN68lURPP1JSI5HJUJ6Ep3+xj40faYEqGxg6aFqWcWqzgmjL/q9pQIawphMd
      HaWoqJD04adYUlqcpWKkk+jhGIj+rKDvBRC9ehMJhA9/lLf/wR/MeE2SpGxSwnlpLWCBXCA8
      Pj5OVVUVvb29czIy8yu8zMcmA3WuAvgrdfLDZWggWldfT+iDf8593/sqdzZVIc7WPSStsLtv
      hJ6SBt72sY8hCAKl5eU8cLyLT109tSj60cOncfVnEITZiWCSIOAVztEjSwx48tFDaPEMlf2Z
      7Eo9CVEQ8CxA+jDd28Nw79RVeczIsPxPr2FdsQPG82jRk6QzhifHpxOomsaD3/0Jzb5SjtXX
      sSwWQOw7xhTvOdIJgHrqxLznY2JCyVBZX7/g8ZcCM12ZSqUoKysjkUjkVvrp1Vr5BmBmg6Yb
      BmT5//kbcVciLkuSfcXq1Wz51Bf4QW+QnolzhJxYWuF3HT3co3ho/YvP80ef/Tw1tbUALF++
      nObb72YicY60JQgCd65bjHvNwgvmXYJMbYdCw4CBU7h8u41OJI7smX+yDgaC3POL33G9JLM4
      GWbdicPY+4Yvyzks83l5+n9+PP/AywCLxUJVVTa+MpulmG2zTL9/tkkuSVKOvpw/0U2hNZML
      dEXvA1RXX562lIqi8JfhEG9e3spINE7HaICRpEJRURFf/vb3ZozPZDJ87prVfGDTStKqyiP7
      Orl5TTOhcIKZoiavLGRBJNw9jjbPZtxYJMLS0XHcl8EVmQ7dMOg9eDDH4Xk5YbpBmUyGZDKZ
      8+vtdnvOxTH3CvJJd+bdwWzCbQbC5us2m41oNJpz1a60u4EMMDAwR1UUsKxtKUdOHmXZ2nWc
      2r+Xiuo6enrPH8T95KVzvWDLq6oYGBiguraW/t6Z7YxCyezqIYgyqRH47s8PUHxW4Xzembut
      gdjJLlwti3CUeIgcPYUSvozKYnYX7nIn6d4uBnBQW+CGYACsNlCm+vBWSUYV8g1EQGpqRSCN
      ejrLQBWrazEmJjCUJKjZwFKqqUPrO/913KGofOBrX3/ZJ78JURTxeDy5Jnom8oPe2Xx6SZIQ
      RRGXy5UrgjH3Fsyg+UL0Pv/t3/7tMnybhUEGqG9eSltrI/uefppr33QLicAoOw+dZdPyVgoc
      do6cPEpFQztldh1XYS0RxWDNsnb6Tx/CV72Y4mI/e595ghWr1xEeH0BxllHuyPDIE8/TumQJ
      wwMDLF+5El20sbStmbOnz2AzonhKaqhY1MYTgptlRgzcJSxNuImRxFpejq+9jnhHJ56Vy0BJ
      Mv78cQo3L8Fe6CZ2sgtHpZfxnUepuGUDgZfO4GuvJXayE+/KpYiSgBpPEz95EmtNPbKUIR0H
      m8+JMtRPpHMIz4rFOIochE6NULi0EmU8RCqq42qoQgv2Yh9z4HZaIZ6GoiJIq2C1QyyWzf5E
      IzRVlvOIAGaxqFjVhJCeQMePXFMK/iqkylIyLx0Cq4zc2IQ+1Ivc1I5YWop68hhSfRNk4qgd
      52ou0prG2YIi3r1q1Wy/28sGSZLwer1EIpFZO9vnPwczNWVNaoUpjHsl0yBgMgbw+r2k8LC6
      fRGRsW7SgsyGFa088tjjjIeyK2s6PIzqLMUlC/i8XgxdpW3FGjx2gzNDUcr8XmQR2pcuoa62
      gh1PPQ9AYVk127Zto7LEj8/rxzCgpc5PXesKNjY2knGU8qMjp3jq0BBeBOyTCmiy14VhCHja
      G9HCE8RDGgXrWons3ENyJI/4r2bQ0pnJ8SLetga08ASZaJzA3hPYa8qQnTY8rfVYfA4mnt2P
      tbIUELF4nFiranGUu4kdOYZo9+KsKmB89xH6tBSNb1hOodsBSiKb/bE7sv8EkWBGRVFVYqkU
      Yp6+p+B2oodC6KEQYmUjRIfQBkYQnF5EqyW7cSaK6IFh1N4RpJJCBKuMNBkbASQ0jQeqavnY
      N7/1qkwei8WCx+OZdfNMluXc3cFc1af7/magLIpijnF6pUIEKC0pQtBVEopCPJEiEU/QNRzm
      lhuvx2nLfrlkIsHO516ksbGGkpISBAQSsRg2VwnrVy3BW1iKXcxKXQ/196FO3vEGujp45pln
      6OweyHZJFwwS8TgJ3UnRyR7qD45zR8CO76VRvCkVbbL00lrkAwy0ZBotqaCn0yR7Ryi8dj3W
      SdUCZAfFV69FnZg4Nz6VnnxPCkPXMTQRi8+BmkyjJlMkdBUtmQZBxFrgRlfS6OkMuqqjJVNo
      GSje0E5RBs4c6wa7G0orIToBmgqaAcWlHH78CR75/s84fPQkQw3VPKRlJ4XW24W8dA3Wpc1k
      jh9HrGhELPZjqAqGrmEkkoj+gmw6VFNBsiNYZUin0Q2D07E4PzFE3vXlr1BcvPBkwOWEIAhY
      rVYcDgc+ny+n2ADnmJ7m3/nBcX7zFHN8KpXK7fyadxJFUXLGIwjCFCqGIAisuPZ2vvyFz/KJ
      D71j1vNrXHsbt629PLqzwqZNm4xLaUu/dvM2GmtK+O19D5C8wPjm/Y563uionH/gZYJq6Lzg
      DVBvdxOdyNCsupGF2QPclKHR0ebkkx9/O45ZqBSnegfo+PWjVIoiITVDt67zZt/F9Ro4E4vz
      u+ERhqtreddf/01W7PZlCKovFmYz7VgsRiaTQRCEKcU3+YxQwzBy8icm0ul0bpKbu8hmP2Sr
      1crw8DCFhYUIgkAikeA/H3iKyP4HWLJ6M9+85/e84213cmrX/Wy98+M4rRo/+N69LKsvIB4Z
      5kcP7rik7yZs2rTJ+MhHPnJJB7lY7PjyN7h9+JWjO0f0DFWbnGyoKCKQSnPfi314xmUCljT+
      jJWoPUOd4sQxmU5VDZ2RdcW87e4bKfbNLNS+59s/5hbLxQeocVXlYUPAdsdbsbrdNDc3s2HD
      hos+3ssFU20iHA7nUp753V+mu0n5+X+z5sAcm7+nYBgG0Wg0xzuKx+MUFhbybz99DAb2kRrr
      okctRkrq1JRGUeVizkYcSBOn+PiH38fH/vjDnBwIXtJ3kwHe9a53XdJBLhZ9u/fDvS++7J9j
      GAYqBkGrwjp3NsYostt47+Z69o8EeVNpFUPxJIt8bn78Qje1o1kDGJAUrC8OsmdFJ7duWj3j
      uP4lrQSOnqLoIrI0nfEEx66+lrs/8ef4/a920nd+JBKJXNcXk9I8V4Cbn0EyXR3zufyMlsvl
      yhmHrut4vV7i8ThdR17kuQe/Q/Oa64mET7BxeTu79h7DEJ0E0xbE5Dh/8icfo2pROycHdnEp
      eFXr1FJOKxlDxzKLGyLYbJBJYywweyba7RjpFLOlmUeNNEq9TqHdRo3nnGvhtMhsrc7q+Hgn
      NX6skyvUgDXDpj+9lUA4yrbVs3dAbqitInV47s0yRddzxzMRVVU6U2ni7/8gH3jXu19RHcxL
      gTmB8/k/pquTX/xiPmeS5Ux3R5blKRpAJvLjCPP4vcdfYjCYZnDH7wE4sPf5Wc+ps/884mcL
      xKtrAIaA8vE7Eb9xPyXXbMOihQgeH0ZAQapchDXVR3wgii7asHltJAaDyB4HaCqWokIyY2MY
      sh2bx4JUVY8w2kdiLEz5G68l8OxelFAcyWljwi7z0W0NiNHzS5ikNI3RiRSlhg3/lkbWtDWe
      NwtTVVTIHsNgOj81kFZ4ZHCU0aDCW1vLqXVlja47muDbx3pY9Zcf5SPvfs8VnR6cDrfbTSgU
      mpIONe8Gpn9vTvT8FGl+QJwfF4iiSDwex+Vy5ejS5vOvJF7V5UcDnjnWQdGyeiQLGJIFW0UJ
      FbdfiyRKWDxOCjatwFpciG/zRvxti6i9+2oEyYKjpozymzdQcsMmZL8bQbYgu20Ubl6Ooeuo
      8RQVb7sVe5GTKm8lQ00r5jV3uyRRVGjDAHSbPO8EnYjGQJt6i8roOgPJFKlBg6syxTzXGeR4
      OMqpaIznOiao3biZD37iz15Tkx+yPr/X68XtducmsizLZDIZFEVBVdVcnXE+zPghnU5PEewy
      5dHtdnvOiMy7yCuJV71Uf0lMwdqwFLWvA7moGHe9ByWhIuoa8e5enCtK8S6tIzk4geS0Edy5
      H7GsGlEJAV6Cuw9RuGUF6eFx4qf78BSXosbiqNEEqZ4eQh1jtHxoM7WSjC6DMY/ixta2EnaL
      41hsGv3jE1QXF846bs+JTvqe3sU21zmXyjAMHuwYRgwKLJd9iIJAa9pD74k0ggFxr5u7//Uf
      rqiCkIXC3O21Wq05EVvz+enljdOV6WRZnmIAkiRhsVimvOflpEi87babOH1w36yvvcoGoLHn
      6D7axhKk+4awFE1gLS1DFAZI9AbQ46AeP4Pk9mJ124j2j2BoaTKJCVyrWwjuO4Fos5M81Ums
      P4iuQOT4WXRNRG6poPPIcUa8QZZlYhgjXRgL2I9Z5HezaL2bsVSU0SeeILlpE821U7lSiVSa
      wT0HuNZmI6aq/PrsMHc0ljOUTJNO6yyVzqVDRUGgVLBx3KJw1Tc/T3Nr6+W+iC87zH0BE6YR
      5OfyFUXJ9ZbINwDTBcpf6ZPJJGNjY3g8nlkD6ks1BndBOR/54B/wz//yHwDc2l5L86LZi3Fe
      VQMoLS3m6VSQgTNnKRStpEeCpEemprW00SCMBpnO9Jl48Uju7/zXlNEgumGwbySAgkZti4eK
      4CD6BWbLSuw2SoDHdu6i8i2345qsXe4eHmXXI09ybUYHSaQjEsMyJvHNRDfFCTseQYa8uhDd
      MDgsJln+tb9n2003zP5hrzGYEzoej+dcHNMdmq3Te/7Kn0wm8fl8RKNRbDZbTrXOZrOh63pu
      n+FSEAsO8+KhhdHOX9UY4FOf+hQf/cJnFqR7s1CkDI2ntGE2uHy80VOGI31pRy9UUvzHj+9F
      m1ztDr64n5t1sIgCHdEYA7EUNbKDq9MlrJB9NErn1Nx6tRQvbV3EG3b8Dze/+fbXnN8/FwRB
      yBXWz+a7z1Z7bBqBmRWqra0lHo/nXCszy2QaxSWeYS4DNR9e9Rhg63XX8jP9axSIl8541AyD
      U2qELc4CCqXsRkwgemkXc21xAXogzHAwTJHHjToa4FA0xoHuCBVJByoC1smd0HwcE1M0/vun
      +MO77rxiFBAuJ0y/P78RnskTmu37mtfHdJ1MOoQsyyiKMsVoLpX96ispJxOLsWZ5O3sPHmNf
      3xhPnT0++/e4pE+6DGhobCDRXgOdC+t2OBdGtBRH1TDtDifVlqy/F9ZVGmovXVpxkcvO3od+
      T8qAQHCc/WfibKYQ+xwTO6ArlPzdB7j97Xe9blb96ciXRcn3983XgBldIs2VPt8lMjfY7HZ7
      LqN0qTFAeGyI3ROj6Ho2tRoQEnQLMxuQwxVgAJIkUbhxOUbncwgX6QzFdZVhMc6b/aVY8zbV
      xow0Dt1OWtOwXcIqXGS3ceNkDPBAf4hrKZ51YhuGwUmSCO++mY9+5MOv28kP5FQg8pWfzdU9
      mUzOKKc0KRG6rpNOp3E6nfj9fgKBwJTKs+maRReD0ppFLGmqobKkgHvu+yV33FbFisWzu0Ov
      ugEANG9Zx8gPd1AmLaw3lGYYPKeOYEXCJ1hJGCpOizBl8gP4BQvjyuWh4sYzKrt6x0iPqAjC
      zFv0GT1J4Ool3PpXH2fV2jWvmR3ei4VJiJu+6pt3BHOHOF9FwgyQHQ4HiqKgKArFxcWMj4/j
      dDpzFWWXitG+M1RWViMMzCzAmo5X3QAEQWDNhvV8T1AoY2EGIAoCFZKdTS4/Ksac941eV5o/
      XNp80UF2TyROidPG7zsGmRhO0xhz0iBOZWnqhsGeIolrv/H/2LLt6telvz8XTL5//ootiuKU
      OgJzZYfsbnIqlco9Z6ZPi4qKGBwcpLS09LLUD7eu3YZXGea5ffM3dXnVDQDI9putLYX+ubX8
      k4bGmJbCLkiMGilGjCSiUID1PNPbExMZjCeoci2cWpzWNB46PshgJkmoO0WR1UaJbmWp6Jk1
      Z/ZSqZX3P/QjauvrFvwZrwdML5vMh0mRMDM8ZkGMKcxrCmblw+xZ7HYvTHX7fBjt7aSgsZa2
      pnqOnDzNrj0BdjxxataxV4QBiKKI4LQDsxtA2tB4QRlnndvLSCbFJrsXUZife58RDDyz5KXn
      QlrT6ArHUc+quKwCgQKBFTEvwixSL5D1+cdCE1jn6PryeoVZ1DK9A7wJ06fP1wrKV4cz64bz
      C2TsdnuuLuBSERwd4kA4QCaTFaYZGVPo6pq99/AVYwCuxQ3QcWDK8xE9w2E1hCTCzb5iPKJM
      vWXhq3lIz2CbR7tU1XUOj4c51RMmOqagWqFNdFGjOVgUc533dqwDktVyRUr+vZwwDCOXq5/t
      +kzP/gD4fL4cV8hUmpi+++vxeC5Lh8jCyloW11dRU1XCz+7/NTfdVE1z8+yp1SvCAARBQHbM
      9P+PaWGu9xRgEUTs4oX51kNqCqNMQtUNbOd56wsDAUL7k9RJdsCevQlN/qaz0bRTuoZVEBnQ
      UvQuq+bOf/gkvousBHutQtO0KXW+040gXwXCbrdjt9unsESdTmcu5ZlOp3P7Bz6fj0AgcMlp
      0InBfmyr16EmZzZfmY4rJlWx4g03MKxNdYGqBAenM4kLnvwA5ZKNhlErj3fPLlJlGAYvDU5w
      dDiEV5x/HVANnecWFxH/0oc4/dHbaLr3n/nM479gyzXbLvjcXuvQdX1GsJpfJyAIAjabDY/H
      g9vtnhEomzvI+QrWcK77zKUGwWWVlex/7jFkV9m8Y6+IOwDA5qu2ssMrUh4/91yRaGOPMsYq
      +0WssALYBYmGonOljFElw1NnR1AzBiEtg9Ct0Sa55qwLzscZI8Wd//Z5Vq6avcnd/yaYlIa5
      JqupWXq+iWy6Q4lEIpcetVqtc6pSXwiCwRBL2pt59OHfArBnzyiPPnps1rFXjAF8/vOf5zep
      QZq0CgrFbG6nX0+y1HbhTZOPpCOMKxkMoONQkkPeIKIkEElkaAo4sCJRhIRFnnvi64bBUT1O
      zCFjj6bg1k0sW77s4r/g6whWq5WCggJ0XScej08RvcqXTD8fzEYd+TRpTdNyTTwuBUoyysGD
      hzB/3lAoQ3fPFRwEAzzxxBMMqAo7Vjlw1FgofmSEsJhgo/XCVSOCWoYlFi9uUc6qQMcnCzOw
      5FZ7y3nSp5phsLutkHd867uk0mm+8sV/5D+++qX/VTn+8yE/u2O6MCbJzaRKz4d8N8hEIpG4
      bGK61914J8WOYX7+y2e4fns1jU2zZ+quGAOwF1Rxy7YS9p3s4q4/u56KP7oN6ccvYX0xibu1
      hvjhY6ixhXUcNAxwCFMnqyAIyAvcEutS4wSWrOCJp54CYOt113D//ffPGNfW1sb27dsXdMzX
      K/KN4UIXCHMjzewhLIoi4XD4kmOAkvrFxAc78DbOzwO7YgygoqGFU49/j7K26xh9NkD7B+oZ
      uWYV8qG9YHXgWdVC8Lmj8x9IECnxeIkZEr70wvUo83FPvI/d3/4uToeFRGJqYC5IMg6LSCKl
      8N73vvd/vQHk40InrjlekiRUVWViYoLy8vJLjgHKCr3YPAW0NVUAz5x37BVjAAOdx1i26QbO
      hAz693Xh/JObKE0P42htIBOKYXVPvbjebVdBZIjI0V6sxX6MRIxMPIPU0sgyr4WgLOM41Udq
      PIrssqOnFGyVJaR6BtAzGqVvuRk1EkMd7CE+EEIUDCR/AdGxIU6GMrSsXEetR+WlY304RIXR
      cIqmhhpGgkk2L6/m4JGOV+lKvX5gkudkWSaRSFBbW0symbxkHtXR/S8AIgcPZveM9uwZ4eGH
      r/AgWImO8vNdT+GwyURjMeQv2tl2IkNo1IJosxBP57k/ggRqFMHtQ65ZhKskA/YGNEHkvkMv
      scpeS31JLVqrE6k0jrfWysizHdgqyvE0lzHy8F4wdNRoAqmgkKqtaxm6/3Fs5cU41zVxQ1cx
      z588jlBUzvZt64mqMoamowT6CMdU/F4PqzdeeIvY/8NM5AvoXg4qNACCiN/nJZPO3r3HQzon
      umcnRV4xBnD33XezdWtf7nFyaJSSgY6skGxi6i1RKqvGVugGh5/MxFnS/cNYanyILhvWpEad
      xYU+OEpGtSEKKqHdx3EtXoXS34dlcVaEVovFiB87gY4VIx0DdxmSEceqFdBgc/JwLIUoW6hr
      bOL06S4O7H+RqpY1LGl20NNzBrm4iaJX9Aq9/iCKIk6ncwprdC5+0YWgdPEWtlUk2XOyj3h/
      iuWbGlh7x+w6q1eMAXzyk5+c8tgwDL5w9/up39mJNN23VCKMP7QTbC5knx09nERJnEHToaau
      jMCxM1gR0HURwdAxkiqpg8fxtFYRfilLiorsP44WS4KUIX5aJRNNo5a2ktx7BGlshMUNpRzc
      u5eTpwco9YiEEwa1qQAvHDqCTQahL0r9Lbe8UpfndQmztjgSiVBUVMT4+DgFBQXzv3EeGNFh
      QmU1tLc00TOPeNYVYwDTIQgCt//1J3jupvewwjo1mtcmJivcU3Eyqcmds1QIAHW0j2MZHasg
      4hNlSsWsUgFKlPD+k7ljZAKhyYOpZELZVSeyL+snRjIBUgVOyquzDE9Fh/qacqLxJE1NTblj
      1OZJmv8fLg52u51YLEY6nc412LjUGMAqaJw8eZJNWzbOO/aKNQCAJUuX8puGchhILPg9RZKV
      h+P9vNlTzn3Rft7mqKZ8gYU2JnytjRzY9fDruqLrSoEoithstpxIViKROG9z7oVgoK+P1tYm
      fveb3wBw6mA/XYOzq0Rc0QYgyzKeTavI3P/crMS02eCXLBSLVk6nE9SITspEG1FdxcDAKy6M
      Gi2MBonH45eFm/5/OD/y+UOmjPolt4TSMwz0D6JPzplEUiMwMbtRXdEGAPC2v/w4/3Pvw2yR
      F1bcbhFE/JKVYS2FKAh0qQkCpAkZGRaJbhpl17zHaAyrvLhrF9ffeOOlnv7/YQEQ81Q1TKLd
      paCieSUrqpx0dvVwpmeAlnVNNN48eyPIK4YNOhfKysrI1M7P6jMhADe4inm7t4obXCUU2mSu
      dhZyraOIAS1Btxo/7/tVw8COyEj/4HnHvd6RSqX49Gc+fcmTcSFwOp0X3eV+Nqxf2UZasLN8
      6eJ5x17xBiBJEo7FTfMPzINDlLAIIqWyjUo5qzLglSxc7y5mWJ9ZdaYbBplJHfZTWoQ+KcbJ
      hx+/LOf/WsW3f/gdfnP0sVklzS83zEqx2VTlLgbHzw6iBAewOl5DVIi5IAgCrvoadOMw4iWu
      ELIgUmd1sFeZYJ01W3pnGAYHMmHSUoZxNcON3iKqrQ4eHQtdjtO/JBw9evSy5MUvBs8c2UVC
      SXDgwAFcrvndxsuBeDye+3cp6Nz3LInaBg7//iEAug51c6rvCq4Jng8rt2+j45v302i99B/C
      KUrIiOzOjGMRRAwDGl12WmwFGGQVJwzDwLN66aWf+CVi+/btjIxcehOIi0HBsnIMVWPr1q2v
      yudfChwuD5qSxGqzQyKNmtFIJ16jQTDAilWr+L3PQkVcw3ER1WEdSoxxLY1TkOlXUhRLVq7z
      F+IUJDRAnryzmPeXpKFT0nphbtfLhU03vJHQqd2c6J1a3ucoW8TyEoUXj/bN8c4Lx9XXXM/O
      p5+gbe1WalrgbEcawZHA4pIZHQ9PHeyq4Zp2O0+/1Dnn8dav28CevZMtsNx1XNMq8/RcUiWe
      Bq5pgaf3dV3y97Da7Pj8hWzbvJrv/PdPaFrbRN2NNbOOfU0YgMPhQNy+hv07nqEobKHNuvAi
      meNKBF002OYu5JnYBH7JgmwB12QZ5GwXYERNU9nacpnO/hIgWPAIGfztK1DLNJZXONAUlZBu
      w+ktIHbmBbZecx2VRW5GIgIuGeqrvQQjcZ7cdYgVy1YQ7D7O2uuuIR4Oc9+99yJ7ytiwZjlG
      KkhF01qUdJyDzz/LmvUr8fsK2fk0+D1WFm1eTsroJ358gPa2cryVrYz1nMJVUofFYuX0yQ5W
      rl9GXetqfvfUblYuXYwSHqBl8xs48eyveX7fcSrLK7nuljuw6BGe3d2NRZZYvfEqljZVcGwg
      QpWsIYgaYZxIFh9ypIsPfWAz9//yEUITs0sZLgThiTFqWlfy9MO/nnfsa8IABEHgjg98kNHO
      owyF45zqidFqXViOPqKrXOfJsna2e4pRDP28xTAAz6dCHP3SF7H967/Me/zvf//7lJUtPEt1
      IShtXEx5gQOnr4qBcAc7n3uaFcuvwmJXeGrnC2xuK6GkxI2/sJSxQDfPPLUPdUsTaVsBTS3N
      qCmNqooKuk4dJqjYsMgidYuasBgqnvIqRvu6OD4QZHlrM4ef3UH58nPuztGRXjYsbqPz17uR
      JA9KpI+dL+7nhpvKePjJ/dx0/QqO7d+DUdBIa1MLqGlKK6s5e+IAz+87J0R75PAhtm3bSpF/
      EJBpaa7FX+hHHg7z3JNPsOG663Cg8vCzL3JDu8ipbi9zqNBcAATaKj08sPv8LbHgNWIAAMtX
      ruRbVXW8ozDET0I9GInZOxTmIybIlKxagiWaIjMZ1JryiaKvECETRUtMZQkmigq5b+AFBnec
      XdB5JZPTOxdcPrjFND9/4DF8VYsodluIp1S6+7oR3V62rmyhp+Mwkt1DJHyW3r4+MnqK7r5h
      VDmMIDupLyvlTH8fipEhqckoGZ3xkWEqfXV0///tnWtsW+UZx3+vr7Hj2G4aJ809qZPSkTbt
      IClNKeuNoqqjg46tZZPGtAoxPk1qUQHt0y5ME9M0VPFhoO3LxjSkTdCuaFDWUjGgNFQ0Ix1p
      aRPHiZs4N8d1fD32ue1DcJq0acNyKwZ+0rFk6xy/Prbf8/TMZDkAAAftSURBVJ7n9n98PiKx
      DLGxFB8NX2RV80ZMahodCAYCJI90YKyQicsxei53YS+q4e7mr9M3MMx9m27j32+fYss3mrky
      MsDlcIYV1cV0+3qISFcTFzt9nThdTmLhISJXQvQgyBSEycQiDPT6kTQdf08vwu5iy7oVBHo6
      qHIq6PpcZ4Dg2LE3Jp51f+TnYu8n0+/Z0tKiv//+3FpNLhbHXnuNkheeo8Rm5WjHAIVRE6WG
      G6c56EsqCJVKxJZV03S5H+nyKJayQrDkY2u8ncy5s8jhMQyuJWSiEtrKMl6OxeiR+/iksxvJ
      6Kbak0/beT8NK+sJhQYp8pSgSTE+PHuO2jovx4+foKamZkHOd9myZbfECLaXFaCkFOSohK4u
      XOuihUNQUlrK2OgQUkblwe/t5rw/B1MhrmXbjh28cOpddl1qZ29jBe/1jfLuUJiqeB7VkwSz
      VH1cLzSiaphW1LBGEpgrK5CCUfLqatHVDImPfVjyl2AWKubaagYTEQ688yrGqlVcuXAKb/N9
      1HtrCYYSbCwowpIZ4rK9lCUiQodkp3ldMzbDwvrIfT7fgvbOmg6/38/DP/sRG8rvJNjTz1/+
      9NK8+edvhq7rpFIpUqkUe/bs4cyZM7N+r6ZN2yHcz6YNzfztlX+w/M46yrdPL12ZUxPAbDbz
      2M9/yYsHD/DdoJ97KovYULGU9lCEty+EuAMX/apEXMgIwKQ72dbVR6pzCG3DOvLXfg2jWaDZ
      3dgLilH8XVjr6jB7llB6UeKhVes5IaUYVhQ0XWUkPEZmbJjgSBIR8qO76rjo66V3MMXug0/w
      5+d/u6Dnu1j+98m43W4Ug0pleSVP/eQgTqdzwcUAsm1Ss6pxcx1vZDTKxttXIqe/QDZAFqvV
      ykNP/ZQ3f7CHB4sLMQpBIJ5kqTAxSArZoLEp/9NSlUyCVNd4UCXR+iHCbCIhKyAMCJNAz8ik
      evpAUdAVjWQ6ROvAJTQVht46AQjyLGZS6fR4XUFfGHQNh7uEwPn/EE7dmiDVQvHsb57lwP4D
      1BrKWL2yYUrq92IwX4oQ3koP7ef+y5q1a2bcN+cmAEBZWRl5jzzKwOG/UmrLY2dVKe+aQpj7
      NMrMk+UvdMh+n5qGPlFWqaF/aqvp0lUtyjVYeXjvXpaVlt50fKPJjNA1nrhtFU7n3DvQfF54
      8uCTCCEod5Wy474dizauEGJCC2g+Ui9OHvsn5RUVHD5yBAB/m48LNzCCc2oCnDx5kra2NmBc
      QyYQHOYxbxUWo4Eql43WZJjEqMqKWUaMC41m9u3bx9Zt2+bzY+cMWa/aH1/8w6LWQkzOBJ0X
      9PEHWZ55hc6pCXD06FEOHTo08fxuTyGPecersuqdBSRllUsjY2A0YzDpaOn/7xbluDFKSzg8
      r5851+jt7cVut+PxeBZtzMk9xuYqiQJw95btREf62dC0mr8ffp3aO7yU3Tt99V5OTQCwsG3j
      PSQtBVxuf4dkcTlJoWPPy0fY8mhc4mE0f4BEwEFRiY4imSEdRx7+bIltm5UCJGXuP0Cuomka
      P/zFj2mpb+LXTz+zaOMKIVBVFUmS5lwNBjAWS1C+zMPSpcUz7vu5T4e+lrrG9RSbopjL12Iz
      pnivbDnmuzYhTAKjw0nV5h24842AwFToxr1zy2d+b5fRNMUm+LIhhGDA34/Luvh2TVYjKKsO
      NxcC3Z0EgiMEemcOZubYCgA9589i85RTlIrRUFnEic5L3OvMxzAyhqnJS2roCph0/GadhqV5
      yJEEgqu28HSElAy+TAKXwQzxuaXi5jJCCNpea517SeIsxzaZTESjUazWuXXciY9dYSzPwJsX
      xpUEu892fTECYaDwYftHjCUzFBaYkFMriQR9fFvorLdZUPsGqVbSdBiHUVMq4T4H9nTfTf/8
      Q0oa/+PfYdf3Hybg91OzfPminc3nkVsRe4CrBnBWKmU2mK12zMgk0xmE0YLJZECVNYTBgME8
      /V89pyZAdXUldSvqJ72iU1K5nJc6/dy1egUMBHACLUUO3goMwVAX6Rm8GQGhsvn+nVRVVX0l
      c3KL0HV9ihzK7GIBRpq37sYx+gH9xkqcyWHW37mDV468TvVaL8Vba6Y9KqdsgP3799Pa2jpl
      O336NBt3PXDdvklJvV5Q6xoGlTSupx/n9oaGiddkWSaRSExpAfQVC082DqCq6ix1gVTeP9WK
      DnhLHJxu7yCjz3wrl1MTYDqEEDiXe0lf40NOaSrD6s09Cu23lbHn0X1TfN5ZVYJUKoWqqoue
      i/NlRAiBwWBAURRUVZ1dGajBTH1dLRVVtXQPRNjasg6jOrOeVE7dAt0I7+pGfIdfpsF91Xvx
      QH0Zr7b1Ucz0VwFN19GcjokOJ263G7japie7ORwOrFbrVyJZC4yqqsTjcTKZzOw6xOga0eDH
      vBGE0PAgwUIPsTPjVXTdZzvp8J2f9rCcXwEA7mhq4px9quvu0licKvV6Y0pHZ1TJ8K8CgaSp
      PPvMr9i3Z++Uq46iKMiyjCzLRKPReQnO5BLBYJDfPf/coq5+2TiAw+GY3bi6SjgSJxYZRdFA
      VxXkT1O5jWYjFnvetNsXYgWwWCzkb9lO//GjlNtt6LpOVzDGauNUj0ZIyfDB+pU0PrSLA/d/
      E5vNNtGoOZuBmG3fOTksH4vFcLlcc9aszBUcDgdrV82cSDafSJI0EQuYHUaaN38LR/gMpzrj
      PPLIbg4d+j0A1Y1ePJtrpj3qf0IHHowA71uiAAAAAElFTkSuQmCC
    </thumbnail>
    <thumbnail height='192' name='Datasheet' width='192'>
      iVBORw0KGgoAAAANSUhEUgAAAMAAAADACAYAAABS3GwHAAAACXBIWXMAABYlAAAWJQFJUiTw
      AAAgAElEQVR4nO3dWXAbWZ7v9y/2hQvAfd8XSaRIUWKR1EJRW0nqqu6Spie63Z7xeGJ8HXHt
      cNhvjvtsPzm8RIztl7HDd+zre339MO7qWroWSRRFiRLFHQB3EiQA7iBBgABBEDuQfmBVdUks
      qVTd0jQZOJ8XRSCXc3ioHzORefKfMkBCEFKU/M/dAUH4cxIBEFKaCICQ0kQAhJQmAiCkNBEA
      IaWJAAgpTQRASGkiAEJKEwEQUpoIgJDSRACElCYCIKQ0EQAhpYkACClNBEBIaSIAQkoTARBS
      mgiAkNJEAISUJgIgpDQRACGliQAIKU0EQEhpIgBCShMBEFKaCICQ0kQAhJQmAiCkNBEAIaWJ
      AAgpTQRASGkiAEJKEwEQUpoIgJDSRACElKb8c3dAOPD3f//3NDU1oVAo3to+E4nEW93fUW3z
      x7yuTyIAR0RLSwudnZ0olW/vVxKPx9/q/o5qmz/mdX0Sp0BCSjtaURUASEYD/Ot//W+ISCr+
      9l/8pxh0f/qv6X/9H/5bZFojF2/epfVU5TefxhkeHqe9vfVP3v/Lhp7c4+tHAxSW1NLUWEPr
      pYto33orP93v/+n/Zmlzl/fv/oa9zWURgKMo6t9m2R3kP/zVXSSvjb//x8dIchW/fv8snz8c
      oPZ0B7e7ftp/2rA8jX/1X/2X/I//0/9CxHmS0Yk5znV08O/+zb9Hr9fw7Fk/1Q3nuNXV9lZ+
      ho4rP2N80sbf/sv/mO5PPmFm4AHPLMtEgnuoSXDnP/grur/6gtzSev7y59ffSptvYmpmjht3
      /4psRYj/+R//UZwCHUUyXRb/2d/9Fabezxkwz5FbdRqlFOTRV7385l/+F8yOPfuj9y2XyZAr
      VShje0TUOTQ3tbAx/ZSY2oBry/kWf4o/cK5v4N3ZovXKR0hSkkstVdz/6itc+zLc7q130uYP
      khL8zX/ynxPfsfHZ4xmaTzeJABxFchl8/cVnBEjnRG0VBdmZlBSXcP3Da/zT//EPNLR2/uR9
      apP7/MM//G9c/8Vf4rDZ0BvzydTrUSV3KT9zFUXER2lZ+Vv9OYpKipF/829WdgGZaWrKysrI
      yMqjvfMqudokxSVlb7XN15LJGX3ew8T8Bq2tjRTl6JAB0j9fD4RX6e3tFVeB3hFxFUgQXuFo
      RTWF7QUC+Hy74kbYOyBuhB0DGenpGI0GcQr0DohTIEF4BREAIaWJAAgp7WidrAlvbPDpI2Jq
      I3VFmUwtLJORVUipUY51ZYtTTa0U5mS8sH7/4252Akl+9uE1nj54hLGkinNNJ4AE3V9+RVJn
      5Pb1y0xbnuCPFHGho56gz8WQZYaYpOREiQHrspPS2kZCLjsej4+G811Y+p+iM+Zx/XLHC+25
      nctMWx2o9EYy5GGcW9s0XrhJSZYW17qDgXE7dz+8wcjzJ3h2dmm99iF5aUoc1inszj1udLXS
      /dVDonINTSdLWLCvYcgrQxlx43J5OHX+fcpy9JiHH5NUF9PaUv9G4/b//uO/5df/4m+xT43h
      DMTFEeBYCm5gmt0kEg6zaF/gvQuX2VixMzRmQi4liMbiL20QJZyQc/lUJl/8/j6bSR3hcPhg
      ydYs8vI2MuMxvPvb7EQkgjsBAPTGfDrbz7K362d+2cXNm7dYt85xruMyGeokKxN9lLfdJh7z
      H+piblExsmiURCKJy7PHrQ9uM2caACC/pIpcQxoAbRe70CuiRONJAKrqT5OmTEIyxu5eiH3/
      Hlabg/ZLV1hZnse56eP6zetYhvsBONveQWw/8MZDV5qrwTy9wrY3SDy4IwJwLClUVNefpELp
      p+TsTRYnR0nIlKQZcrhy7QazltGXNpAjSRL7+zGyszI42dCC37fJwoyFjd0IUihATJZk+NkQ
      0ZCfWbuNybEhnOvL/O7rfu7e+QAZEhJJkEHv159T3HSFhop8QoF9ZMnDXZQkJRe7OvF4XEhA
      MrZPLBbj6dDYC+t1f/Epte23yYx7GbHMfPd5fG8bfelJqrOVNF28wax5FORqui63Mzw8Slpm
      9h81dCpDObGdOeRaIyBOgY4nTR5lRgcbwRzek7yshKJcuHCeDFmInp4emt87/9IGSkoLs1n0
      J7jS9R7D/U/IyS+jrqEBgJ3BZyTyi+k60wAEqSrZpbquCPfSPAajnuGxcS6ca+Rhdw9nOi5j
      ef4A+6yFptbzJMefk19ceaiLG44FFlednDjRgFEVoafPwtX3b6JVyli1zeN2u5hZcJCUJbFO
      jtHSfom2lgLmJ8dwud2sBWvJStjZ0+WhDe8QioS50HEJt3uVcFzF5a5WIMHQ0wFcO/us2HQk
      DfkENnaIxvyca/3hyYKllaWEd7fIP3Uaz5pWTIU4KsRUiHdH3AcQhFcQARBS2tE6VqWwUChE
      KBRCJpO9tX1KkvRW93dU2/wxr+uTCMARIZPJkMlkyOVv76CcTCbf6v6Oaps/5nV9Olo9FYR/
      ZiIAQkpTAP/Nn7sTAvzN3/wN5eXlb3z+vDAzzvzSJvmZKp4NDJFQ6HGvLTA9t4DbH6K4IPeF
      c9/5aTOz9nUqSosZHx1g0xumMD8HAPPwc9Y9AYoL8nCuzOJ0J8jJTice3uP5wDDbu0EylXGe
      DY6Qll3IinWCqZkFCkrLMQ/14QnEKcg7uDH1bZuezVXGLBOE4wpifhcjpgkKyypQyWVE9n0M
      jE1TUVbMtHmE6Tk7xeUVKOXg215nenGd4sJcTEP9OJw75KTJ6R8YBm0mftcKY+ZJCsoqUSlk
      LC1O4fEnyTamv3Ksvj8OT3qfUFFViWvVjn1L3Ak+nmI+TJN2jEYjg2MWLl+9hm12gvrGs5Rn
      a8jIKX5pgwRrm15q0sMMjAxh9yQwZh3cCU3sOvDKCwlvO4lIUawOOxu2TQCSqLjY2Ylr1c6g
      eZZr168xNTJIVX0jdXkKhgd6kBe2sO1cPtTF7IJS2s81s2S3MruwxLXOFgYHDu4Ch2OgIAFA
      zakmyjIiLHkOpmagSiMR9EF8F7dPRczj4ollkivXrjE/ZcK+tMG1y6309w8BYMzNwePcfOOh
      i2zYmFndZXFlA/eGTQTgWIruoTSUEVufpKTuNE/7nuLxhwCwbvipL858aYODJ6LS9Co217Yo
      O9HIpGUY29wEK2sbKHRpqJDz4PefEIhJzDvsTJtH8IfC3PvsU5o7LiOTK5AhQybJsE6ZWItl
      0ZinRpem/8ETaZksjmlkHG1aOgqZHJlKT3xvg+cjZgxGI98e5+bGh/GqSylR7jI2MYfR+E0w
      IzGCsV2C0TDNJ07R19ePdz9MeWkBg6ZpEvEowHfrvylDWSN765MoFQdVisRVoOMorYxC7SzO
      sI7zegVOGTQ1NRH0LFFS2/IDG6jRKpI8twb46M4tHnU/QZeeRc3JZiDB0v37BHRZfHTnN4Af
      i8FF49latuZHCWkMrC4vUV+ey6NHPZSdaGS8v5v8kgoU1S2s9T9El5V/qMV1xxJxuQyNWkeG
      TkZPdw9Nl25TaNCw5rDicNjIyi/AarNTWArx2hpamwuwTpuxORzklxShUUgg06BWKVCQoPl0
      C0rZPqFAgPcuXAUSjDwfwLbkpqhA+81UCC+xuJ+Ws2d/cOgyjZmEvCvknWnHvTQupkIcFV9/
      /TWdnZ3iMug7IC6DCsIriAAIKU18BzgiFAoFCoXirZ4+vO07y0e1zR/zuj6JABwRKpUKlUol
      pkO/A2I6tCC8ggiAkNJEAI4p3/YGpql5kJKYhgcJROJEQ34GBkeJJw9f2fa61pm1rQCwsbTA
      vH3tu2XrDisrTg8AQd82W56975bNT5pY3dxBSsYYGR4lnjxoe9QygwQ4rNM4PYcfio+FAwz0
      P8O3HyEW9DNqmX5huXPz4O7tztYqpsm5PyyQkmxuHpRMX7XPsbC0Ack4o0ODBGNJQv6dF/YV
      jwRw7+zxphYXFgAI7bpZ3fKIABxLyTCDpnlOVJUy1N9DxcnTdN+/T/fjZ5xrrqX78cvvD5Do
      HzETWZ/CtrTAvCtJaUHWwZKQC7PNx5R5kAQwaH7C1PDBf5Kgz0VGUS2W4Wc86X5IXX01Pb39
      ePwhytRuegeHsPlUmAf7DnVxPxShteM8fY/u87D3CdV5CvpNiwC41h30D40D4A1EyY6sMOE8
      uJPtWJhjfHIG4l4m57wsT5rp6eultuE03ffv8fTZMNV5Sh4PH4Rgdm6S+ZmFNx660a+/ZGU3
      xuj4DLNTwyIAx5J/Heu6l68++RhddgmWsTH2AlGydHIe9jwmt/DlmvsR9No06irzefrEhHfP
      zcdf3GNhxoJtdoq00mryFTpMk0PUNhy8IWZybIh90lmZHqK46iRhhQajMRtVNIxeEWdgKUKd
      1ktpdR0K3eGXHxmzMnl27wt0xmI0Ch3ZJfXsbYzxdGiM/JIqinINAKilCBNuJZVqPyOWGarq
      GzDo1YCWXa8D116I8qICTGMmdsNRsgxaZpe97PnWAWg604LiJzx/U9F8jtVJM3KFAjniFOh4
      MlZQkRlDoVKRm5uHUiZRVV1BOBxBn57Jvtfz0gZaQgEP9wZs3LlzlZjXg0qtpq6hhdoz5/GY
      e7GFguRqM7DPjjNrt9HU2kFi3cSow08kHKQ4Q0V39wN0RUX89pPPMOpVaItOY+79jFAwcaiL
      a3Y7iowswqEAKnWcB199Tnnj+1zuaGXVNo/ZbGJmwcHvPvuUTK2cpC6btpYG5ifHMJnN2OwL
      JFRpaAijzsxHQYKaiiryC/IJ7bk51dDGQVWIPkzmMVZssyy5PUxNLGAaGzvUnz9QEfHMYyg9
      qIghpkIcEaIqxLsjLoMKwiuIAAgp7Wgdq1JYLBYjFouRSBw+n/5jJZPJt7q/o9rmj3ldn0QA
      johEIkEikUCS3t5XsmQy+Vb3d1Tb/DGv65M4BRJSmgiAkNJEAISUJr4DHEtJur/+grTccnJ1
      cdbce8QkNemyfSKxGNllTbScfPGt7199/jGRSJJrH7xPX+8g5dW1tDTWQWKfjz++R1Kj5Vd3
      f85Q3yf4w1XcutVCcHeb0Yk5tnf81BUZcAci6LOL0MZ87GxtkHviHHMT02i0Gu7+/NYL7Xk2
      V5lZXGI/kiBdHiESDVNU30lDVQ7bG0t090/w17++w9jgU9ybG9RevktNjpalhRkmrGvc+dkF
      Pv5tD5IEtaeK8O4ESSp1qCM+ovEo+bXtNNUWMj72hN2Qga7OH3oW+rB/+O/+e/6j//pfYR1+
      wsZ+VBwBjiX/MosuCe+mk0A0hkyuxO1yE4/F0Gbksbz88tyYMPqMPG6dr+HLzx8hpRtxOjew
      zU1gmxwhr+UqNfo07OuLpBXWoAamzSMEpTQqi3IwZuWxtR/n+vUbhF1bnG5qIhCTo/Jaabn6
      C/Rph/+O5hQWktjzodJkEo+ruXH7I9bnenk+YiavuJKq0kIAmpqbCElq0uMHVSEq6xoozM4A
      uZZkYp+ITEIeiyNTqHFuu4jF4uiNhaw4pgA409qO9ie8lvhcxzmmx2eJyjSkq8Up0PGUlk9F
      gYEyg0R2WRMXO94jP8/IufNdnKrIo7Do5blAGsLRIPYVDx0dDRgy85CSIWpONlN98jTB9SU8
      UoRd5zbezVXmHXYaz7ahCa2x4Ja40dWOLhnDt7tDQqvn6/uP+ODuL6mqrmV9aREpEj3URY/L
      S+etDwntuYhJEXaci2QWn+Ni24vVGu519/LRX/ySgoICWptPfvd5YncNXdkZ6rKUGKrOcLG9
      hcKsLNo6r1BXYqSwpOaF/UQCO/iCIVxbO2w6na8eO2UmSd88GkMJICrDHRk/qTKcXE12uoKo
      roCqgnTM5ik6Llwgtr/DkjvEe00HL4z7Q0U0GbkGPWF1DvU1NSjC2xSU1mFI1yNT6tHLg+SU
      1HCyvp6KiipqqyvR6tQkEhJbGys43btcuNDGzLSVjvNthPc82OxLZJU1kBZ3U1LTSLpe80Kb
      cmKMjVlobb9AfWUx1lUfbWcO+rXmsOLx+gjFQSuLYnMsY8grRqtSYJ024wuEkGeWUqAJocqt
      oCJHh3lilvMXzxP2b7PuT3L2VDUHZVEGCccjpBuyUao1JKJxJClBesYfXhL4/cpwmYZMsnOK
      KK8sIScrS8wFOipEWZR3R5RFEYRXEFeBjghJkpAkiWTyB165+Cfs823u76i2+WNe1ycRgCNC
      p9Oh0+nEdOh3QEyHFoRXEAEQUpoIgJDSjtbJmvBGEpE9ng6MYV90cPcvbjIwMkNeQTFZqgjL
      zi1qGy9QVZL1wjb9j7vZCST52YfXePrgEcaSKs41nQASdH/5FUmdkdvXLzNteYI/UsSFjnqC
      PhdDlhlikpITJQasy05KaxsJuex4PD4azndh6X+KzpjH9csdL7Tndi4zbXWg0hvJkIdxbm3T
      eOEmJVlaXOsOBsbt3P3wBiPPn+DZ2aX12ofkpSlxWKewO/e40dVK91cPico1NJ0sYcG+hiGv
      DGXEjcvl4dT59ynL0WMefkxSXUxrS/0bjZ156Cne/Qj5ZfWcrisXR4DjSKHJ4OrVKxSXFWMZ
      n+f2z27hd7tYdnm4eesDrHOml7aIEk7IuXwqky9+f5/NpI5w+OCNLNGtWeTlbWTGY3j3t9mJ
      SAR3AgDojfl0tp9lb9fP/LKLmzdvsW6d41zHZTLUSVYm+ihvu008drguUG5RMbJolEQiicuz
      x60PbjNnGgAgv6SKXEMaAG0Xu9ArokTjB1dpqupPk6ZMQjLG7l6Iff8eVpuD9ktXWFmex7np
      4/rN61iG+wE4295BbD/wxmPnDoS4fv19NlbmGep/JAJwXNks/VQ3XSBdCfuxJMiSB7c0kzFk
      qF5aW44kSezvx8jOyuBkQwt+3yYLMxY2diNIoQAxWZLhZ0NEQ35m7TYmx4Zwri/zu6/7uXvn
      A2RISCRBBr1ff05x0xUaKvIJBfaR/cAVRklScrGrE4/H9U239onFYjwderFiQ/cXn1LbfpvM
      uJcRy8x3n8f3ttGXnqQ6W0nTxRvMmkdBrqbrcjvDw6OkZWb/UeOWTEqAhJSUiCUV4hTouJLS
      CqkvzkTKv0jv4x4q60+TrY7S3dNHx+WrL62tpLQwm0V/gitd7zHc/4Sc/DLqGg5Kg+wMPiOR
      X0zXmQYgSFXJLtV1RbiX5jEY9QyPjXPhXCMPu3s403EZy/MH2GctNLWeJzn+nPziykP923As
      sLjq5MSJBoyqCD19Fq6+fxOtUsaqbR6328XMgoOkLIl1coyW9ku0tRQwPzmGy+1mLVhLVsLO
      ni4PbXiHUCTMhY5LuN2rhOMqLne1clAWZQDXzj4rNt03b4jZIRrzc6619QfH7WRlGY8e9dDc
      epG4d1VMhTgqRFmUd0fcBxCEVxABEFLa0TpWpbBQKEQoFHrjF2W/ie9PA/7n8udo88e8rk8i
      AEeETCZ7668XEtOhD4jp0ILwCiIAQkoTj0QeET/lkchEJMCz54NMWCYprSpj4OlT4nItOnmU
      oQkr5SUHD5x//9x3ftrMrH2ditJixkcH2PSGKczPAcA8/Jx1T4DigjycK7M43QlystOJh/d4
      PjDM9m6QTGWcZ4MjpGUXsmKdYGpmgYLScsxDfXgCcQrysl9o07O5yphlgnBcQczvYsQ0QWFZ
      BSq5jMi+j4GxaSrKipk2jzA9Z6e4vAKlHHzb60wvrlNcmItpqB+Hc4ecNDn9A8OgzcTvWmHM
      PElBWSUqhYylxSk8/iTZxvRXjtf3x2G47zFWm4Pc4nI0Srk4AhxHCk06XV1daPUapocHaLl0
      jeXFWaJJBclk5Ae2SLC26aUmPczAyBB2TwJjlvFgya4Dr7yQ8LaTiBTF6rCzYTt4fVESFRc7
      O3Gt2hk0z3Lt+jWmRgapqm+kLk/B8EAP8sIWtp3Lh1rMLiil/VwzS3YrswtLXOtsYXDg4C5w
      OAYKDmp11pxqoiwjwpLnYGoGqjQSQR/Ed3H7VMQ8Lp5YJrly7RrzUybsSxtcu9xKf/8QAMbc
      HDzOzTceOwkdVzsbGXv4kIk1vwjAceVbncNQcoJQQo5eJQPkGIzGV6ydQKFQkKZXsbm2RdmJ
      RiYtw9jmJlhZ20ChS0OFnAe//4RATGLeYWfaPII/FObeZ5/S3HEZmVyBDBkySYZ1ysRaLIvG
      PDW6NP0PnkjLZHFMI+No09JRyOTIVHriexs8HzFjMBr59jg3Nz6MV11KifKgLIrxm58hEYkR
      jO0SjIZpPnGKvr5+vPthyksLGDRNk4gfVKIwvvJn/mEbK4v0DczxXmslvlBcXAU6rha29mh7
      7ySRIiUPu3vILyxm2TbHit2ONb+E+qrS762tRqtI8twa4KM7t3jU/QRdehY1J5uBBEv37xPQ
      ZfHRnd8AfiwGF41na9maHyWkMbC6vER9eS6PHvVQdqKR8f5u8ksqUFS3sNb/EF1W/qH+rTuW
      iMtlaNQ6MnQyerp7aLp0m0KDhjWHFYfDRlZ+AVabncJSiNfW0NpcgHXajM3hIL+kCI1CApkG
      tUqBggTNp1tQyvYJBQK8d+EqB1UhBrAtuSkq0H4zFcJLLO6n5ezZQ30CONl8jlPNpyDixTc2
      KqZCHBWiKsS7Iy6DCsIriAAIKU18BzgiFAoFCoXirZ4+vO07y0e1zR/zuj6JABwRKpUKlUol
      pkO/A2I6tCC8ggiAkNJEAI6hRGSPx48f8/jxUyIJmLaM4g/GiEf2ef58kEj88EO6Xtc6s7YV
      ADaWFpi3r323bN1hZcV58Hb5oG+bLc/ed8vmJ02sbu4gJWOMDI8ST4Jve4NRywwS4LBO4/Qc
      fig+Fg4w0P8M336EWNDPqGX6heXOzYO7tztbq5gm5/6wQEqyubkFwKp9joWlDUjGGR0aJBhL
      EvLvvLCveCSAe2ePNzVjGWHINPndtX8RgGPooCrEVaLhADbLU1T51fQ97mFtY4vW1tM8eNj7
      0hYS/SNmIutT2JYWmHclKS04KJsihVyYbT6mzIMkgEHzE6aGD16wEfS5yCiqxTL8jCfdD6mr
      r6antx+PP0SZ2k3v4BA2nwrzYN+hPu6HIrR2nKfv0X0e9j6hOk9Bv2kRANe6g/6hcQC8gSjZ
      kRUmnCEAHAtzjE/OQNzL5JyX5UkzPX291Dacpvv+PZ4+G6Y6T8nj4YMQzM5NMj/z8gtBXm3X
      F6ehVMOzxwMsuYMiAMdVbG8TRUYRK7tR6oqz0SrUFOUZ+erLB5y/1PnS2hH02jTqKvN5+sSE
      d8/Nx1/cY2HGgm12irTSavIVOkyTQ9Q2tAEwOTbEPumsTA9RXHWSsEKD0ZiNKhpGr4gzsBSh
      TuultLoOhU57qH/GrEye3fsCnbEYjUJHdkk9extjPB0aI7+kiqJcAwBqKcKEW0ml2s+IZYaq
      +gYMejWgZdfrwLUXoryoANOYid1wlCyDltllL3u+dQCazrSg+AnP36wvWRmdsFFRoGbJExIB
      OK6ePrfQeaGF1spCPvv6AQm1ht/+f78lMysbv8/30tpaQgEP9wZs3LlzlZjXg0qtpq6hhdoz
      5/GYe7GFguRqM7DPjjNrt9HU2kFi3cSow08kHKQ4Q0V39wN0RUX89pPPMOpVaItOY+79jFDw
      8Euo1+x2FBlZhEMBVOo4D776nPLG97nc0cqqbR6z2cTMgoPfffYpmVo5SV02bS0NzE+OYTKb
      sdkXSKjS0BBGnZmPggQ1FVXkF+QT2nNzqqGNg6oQfZjMY6zYZllye5iaWMA0NnaoP98qqazn
      2vsfUF5WiMMyIKZCHBWiKsS7Iy6DCsIriAAIKe1oHatSWCwWIxaLkUgcPp/+YyWTybe6v6Pa
      5o95XZ9EAI6IRCJBIpFAkt7eV7JkMvlW93dU2/wxr+uTOAUSUpoIgJDSRACElCa+AxxDiUiA
      /iETplELv7xzgwn7Jhq1jvrSLFbWN5Gn5dD5XvML23z1+cdEIkmuffA+fb2DlFfX0tJYB4l9
      Pv74HkmNll/d/TlDfZ/gD1dx61YLwd1tRifm2N7xU1dkwB2IoM8uQhvzsbO1Qe6Jc8xNTKPR
      arj781svtOfZXGVmcYn9SIJ0eYRINExRfScNVTlsbyzR3T/BX//6DmODT3FvblB7+S41OVqW
      FmaYsK5x52cX+Pi3PUgS1J4qwrsTJKnUoY74iMaj5Ne201RbyPjYE3ZDBro6W95o7D75f/49
      xkIDueWtpOMRR4DjSKFJp+tSG41nzmJdc/GLWzdQxqIUFRbg297AkFXw0hZh9Bl53Dpfw5ef
      P0JKN+J0bmCbm8A2OUJey1Vq9GnY1xdJK6xBDUybRwhKaVQW5WDMymNrP8716zcIu7Y43dRE
      ICZH5bXScvUX6NMO/x3NKSwksedDpckkHldz4/ZHrM/18nzETF5xJVWlB7WLmpqbCElq0uMH
      VSEq6xoozM4AuZZkYp+ITEIeiyNTqHFuu4jF4uiNhaw4pgA409qOVvETx0+hQqlUEIlERQCO
      q7Hnzzl38SJVRi2LTi9R4uzuR/nw7i9Zt82+tLaGcDSIfcVDR0cDhsw8pGSImpPNVJ88TXB9
      CY8UYde5jXdzlXmHncazbWhCayy4JW50taNLxvDt7pDQ6vn6/iM+uPtLqqprWV9aRIpED/XP
      4/LSeetDQnsuYlKEHecimcXnuNj2YrWGe929fPQXv6SgoIDW5pPffZ7YXUNXdoa6LCWGqjNc
      bG+hMCuLts4r1JUYKSypeWE/kcAOvmAI19YOm07nK8etuLwWKR7DkAkra/uiMtxR8VMqwwFo
      M43kZKSRXVjGlmOWxrPtEA0wMWPnUucFFHLZ9yqiycg16Amrc6ivqUER3qagtA5Duh6ZUo9e
      HiSnpIaT9fVUVFRRW12JVqcmkZDY2ljB6d7lwoU2ZqatdJxvI7znwWZfIqusgbS4m5KaRtL1
      GuAPVdjkxBgbs9DafoH6ymKsqz7azhy8yG7NYcXj9RGKg1YWxeZYxpBXjFalwDptxhcIIc8s
      pUATQpVbQUWODvPELOcvnifs32bdn+TsqWoOyqIMEo5HSDdko1RrSETjSFKC9E6HEBoAAA7Y
      SURBVIyM78bq+5XhMg2ZnGg8TdC/j14TF3OBjgpRFuXdEWVRBOEVxFWgI0KSJCRJIpn8gVcu
      /gn7fJv7O6pt/pjX9UkE4IjQ6XTodDoxHfodENOhBeEVRACElCYCIKQ0cR/giPi7v/s7ysvL
      3+gSYiKyR9+zAR497KW8PI9HTwbx7oUoLcrnwT/976jL3sOgefHyX//jbsanFqmuLefJ/W68
      oQRFBblAgu4vv2RxzUVtVQXTlifYlqOUleYQ9Ll4NjjCgmMNZWyXEdM4UbmWVes4UxMTaHMK
      efrwIWsuL1UVB+XYv23T7VxmxGRhY9uHb3OJcYsZbW4FmTolrnUHD5+ZOFlXzcjzJ0yOT2Ao
      qSFNLcdhncI0ZaO6ooDur+4zZ1tBq4wyarKwE4jhWplnwmJBnVOGQa/CPPyYje0oxYU5rxyv
      b/uUiOzR1/0F3aOLVFZWotcoxRHgODooi3KF4rJiLOPz3P7ZLfxuFxv2aWQqDcHYy1tECSfk
      XD6VyRe/v89mUkc4fPBGlujWLPLyNjLjMbz72+xEJII7AQD0xnw628+yt+tnftnFzZu3WLfO
      ca7jMhnqJCsTfZS33SYeO1wXKLeoGFk0SiKRxOXZ49YHt5kzDQCQX1JFriENgLaLXegVUaLf
      1DKqqj9NmjIJyRi7eyH2/XtYbQ7aL11hZXke56aP6zevYxnuB+Bsewex/cCbj1v7aUpPnCO4
      vcSDT/9JBOC4sln6qW66QLoS9mNJkCUZNY3jc29ht9teWluOJEns78fIzsrgZEMLft8mCzMW
      NnYjSKEAMVmS4WdDREN+Zu02JseGcK4v87uv+7l75wNkSEgkQQa9X39OcdMVGiryCQX2kf3A
      FUZJUnKxqxOPx4UEJGP7xGIxng69WLGh+4tPqW2/TWbcy4hl5rvP43vb6EtPUp2tpOniDWbN
      oyBX03W5neHhUdIys/+k8bPbbKhkYXEZ9LiS0gqpL85Eyr9I7+MeKutPU1fxPn7nAlFDzUtr
      KyktzGbRn+BK13sM9z8hJ7+MuoYGAHYGn5HIL6brTAMQpKpkl+q6ItxL8xiMeobHxrlwrpGH
      3T2c6biM5fkD7LMWmlrPkxx/Tn5x5aH+bTgWWFx1cuJEA0ZVhJ4+C1ffv4lWKWPVNo/b7WJm
      wUFSlsQ6OUZL+yXaWgqYnxzD5XazFqwlK2FnT5eHNrxDKBLmQscl3O5VwnEVl7taOSiLMoBr
      Z58Vm+6bN8TsEI35Odfa+sMDp8uhtkhNQl3Izo5GTIU4KkRZlHdH3AcQhFcQARBS2tE6VqWw
      UChEKBR64+nQb+L704D/ufw52vwxr+uTCMARIZPJ3vrrhcR06ANiOrQgvIIIgJDSxFSII+Kn
      PBKZiAR49nyQCcskpVVlDDx9SlyuZc+zzsTUDOo0Axl67QvnvvPTZmbt61SUFjM+OsCmN0xh
      /sH0AfPwc9Y9AYoL8nCuzOJ0J8jJTice3uP5wDDbu0EylXGeDY6Qll3IinWCqZkFCkrLMQ/1
      4QnEKcg7uDH1bZuezVXGLBOE4wpifhcjpgkKyypQyWVE9n0MjE1TUVbMtHmE6Tk7xeUVKOXg
      215nenGd4sJcTEP9OJw75KTJ6R8YBm0mftcKY+ZJCsoqUSlkLC1O4fEnyTamv3K8vu1TIhLg
      WV8vltkl8otK0KnFVIhjSaFJp6urC61ew/TwAC2XrrG8OMvc1BRqXSb5OcaXtkiwtumlJj3M
      wMgQdk8CY9bBOoldB155IeFtJxEpitVhZ8N28PqiJCoudnbiWrUzaJ7l2vVrTI0MUlXfSF2e
      guGBHuSFLWw7lw/1MbuglPZzzSzZrcwuLHGts4XBgYO7wOEYKDio1VlzqomyjAhLnoOpGajS
      SAR9EN/F7VMR87h4YpnkyrVrzE+ZsC9tcO1yK/39QwAYc3PwODfffNxaqtEVn2Ldaubh/fsi
      AMeVb3UOQ8kJQgk5epUMkHP77q8421DBg8fPX1o7gUKhIE2vYnNti7ITjUxahrHNTbCytoFC
      l4YKOQ9+/wmBmMS8w860eQR/KMy9zz6lueMyMrkCGTJkkgzrlIm1WBaNeWp0afofPJGWyeKY
      RsbRpqWjkMmRqfTE9zZ4PmLGYDTy7XFubnwYr7qUEuVBWRSj8ZtgRmIEY7sEo2GaT5yir68f
      736Y8tICBk3TJOIHlSi+Xf+nmp+eQ62IiKtAx9XC1h5t750kUqTkYXcP+YXFWKctbLq91FSd
      eGltNVpFkufWAB/ducWj7ifo0rOoOdkMJFi6f5+ALouP7vwG8GMxuGg8W8vW/CghjYHV5SXq
      y3N59KiHshONjPd3k19SgaK6hbX+h+iy8g/1b92xRFwuQ6PWkaGT0dPdQ9Ol2xQaNKw5rDgc
      NrLyC7Da7BSWQry2htbmAqzTZmwOB/klRWgUEsg0qFUKFCRoPt2CUrZPKBDgvQtXOagKMYBt
      yU1RgfabqRBeYnE/LWfPHuoTAEodWelqik+fwhuIiqkQR4WoCvHuiMuggvAKIgBCShPfAY4I
      hUKBQqF4q6cPb/vO8lFt88e8rk8iAEeESqVCpVKJ6dDvgJgOLQivIAIgpDQRgGMoEdnj8ePH
      PH78lEgCpi2j+IMxSMYZHRrAHzr0VDxe1zqzthUANpYWmLevfbds3WFlxekBIOjbZsuz992y
      +UkTq5s7SMkYI8OjxJPg295g1DKDBDis0zg9hx+Kj4UDDPQ/w7cfIRb0M2qZfmG5c/Pg7u3O
      1iqmybk/LJCSbG5uAbBqn2NhaeObn2uQYCxJyL/zwr7ikQDunT3elNfjBcDj9eLxekUAjqOD
      qhBXiYYD2CxPUeVX0/e4h2dPHlPffA6l9PIrQSX6R8xE1qewLS0w70pSWpB1sCTkwmzzMWUe
      JAEMmp8wNbwAQNDnIqOoFsvwM550P6Suvpqe3n48/hBlaje9g0PYfCrMg32H+rgfitDacZ6+
      R/d52PuE6jwF/aZFAFzrDvqHxgHwBqJkR1aYcIYAcCzMMT45A3Evk3NelifN9PT1Uttwmu77
      93j6bJjqPCWPhw9CMDs3yfzMwhuP3diwCYDhsWH+3f/5f4kAHFexvU0UGUWs7EapK85Gq1Cz
      ub2OefAZg6bpl9aOoNemUVeZz9MnJrx7bj7+4h4LMxZss1OklVaTr9BhmhyitqENgMmxIfZJ
      Z2V6iOKqk4QVGozGbFTRMHpFnIGlCHVaL6XVdSh02kP9M2Zl8uzeF+iMxWgUOrJL6tnbGOPp
      0Bj5JVUU5RoAUEsRJtxKKtV+RiwzVNU3YNCrAS27XgeuvRDlRQWYxkzshqNkGbTMLnvZ860D
      0HSmBcUf9fyNkhNnzogAHFdPn1vovNBCa2Uhn339gIRaQ3VZJfEkqA5d8dASCni4N2Djzp2r
      xLweVGo1dQ0t1J45j8fciy0UJFebgX12nFm7jabWDhLrJkYdfiLhIMUZKrq7H6ArKuK3n3yG
      Ua9CW3Qac+9nhIKHX0K9ZrejyMgiHAqgUsd58NXnlDe+z+WOVlZt85jNJmYWHPzus0/J1MpJ
      6rJpa2lgfnIMk9mMzb5AQpWGhjDqzHwUJKipqCK/IJ/QnptTDW0cVIXow2QeY8U2y5Lbw9TE
      AqaxsUP9+ZaCfR49vE9WXgmaZERMhTgqRFWId0dcBhWEVxABEFLa0TpWpbBYLEYsFiOROHw+
      /cdKJpNvdX9Htc0f87o+iQAcEYlEgkQigSS9va9kyWTyre7vqLb5Y17XJ3EKJKQ0EQAhpYkA
      CClNfAc4hhKRAP1DJkyjFn555wYT9k00ah2VeTrWVu34FOX85c22F7b56vOPiUSSXPvgffp6
      BymvrqWlsQ4S+3z88T2SGi2/uvtzhvo+wR+u4tatFoK724xOzLG946euyIA7EEGfXYQ25mNn
      a4PcE+eYm5hGo9Vw9+e3XmjPs7nKzOIS+5EE6fIIkWiYovpOGqpy2N5Yort/gr/+9R3GBp/i
      3tyg9vJdanK0LC3MMGFd487PLvDxb3uQJKg9VYR3J0hSqUMd8RGNR8mvbaeptpDxsSfshgx0
      dba80dg9evCY67eu8uBRN9bJWXEEOI4UmnS6LrXReOYs1jUXv7h1A2UsSn3jWRTKTH5+o+2l
      LcLoM/K4db6GLz9/hJRuxOncwDY3gW1yhLyWq9To07CvL5JWWIMamDaPEJTSqCzKwZiVx9Z+
      nOvXbxB2bXG6qYlATI7Ka6Xl6i/Qpx3+O5pTWEhiz4dKk0k8rubG7Y9Yn+vl+YiZvOJKqkoL
      AWhqbiIkqUmPH1SFqKxroDA7A+Rakol9IjIJeSyOTKHGue0iFoujNxay4pgC4ExrO1rFHzOK
      KuqbmkUAjqux5885d/EiVUYti04vUeIkI7vElJloDv1WNYSjQewrHjo6GjBk5iElQ9ScbKb6
      5GmC60t4pAi7zm28m6vMO+w0nm1DE1pjwS1xo6sdXTKGb3eHhFbP1/cf8cHdX1JVXcv60iJS
      JHqofx6Xl85bHxLacxGTIuw4F8ksPsfFtherNdzr7uWjv/glBQUFtDaf/O7zxO4aurIz1GUp
      MVSd4WJ7C4VZWbR1XqGuxEhhyYsvAYkEdvAFQ7i2dth0Ol85brFYiNCeG1Q6SCREZbij4qdU
      hgPQZhrJyUgju7CMLccsjWfbIRahtLoG1Tezw/5QGU5GrkFPWJ1DfU0NivA2BaV1GNL1yJR6
      9PIgOSU1nKyvp6KiitrqSrQ6NYmExNbGCk73LhcutDEzbaXjfBvhPQ82+xJZZQ2kxd2U1DSS
      rte80KacGGNjFlrbL1BfWYx11UfbmXoA1hxWPF4foThoZVFsjmUMecVoVQqs02Z8gRDyzFIK
      NCFUuRVU5OgwT8xy/uJ5wv5t1v1Jzp6q5qAsyiDheIR0QzZKtYZENI4kJUjPyPhurL5fIa+k
      KIeJ+VU6z79HcU6GmAt0VIiyKO+OKIsiCK8grgIdEZIkIUkSyeQPvHLxT9jn29zfUW3zx7yu
      TyIAR8T8/DxqtRqF4o+6pPGDEonEW93fUW3zx7yuT+I7gJDSxHcAIaWJAAgpTQRASGkiAEJK
      EwEQUpoIgJDSRACElCYCIKS0/x/bghr2jfEHqwAAAABJRU5ErkJggg==
    </thumbnail>
    <thumbnail height='164' name='Deceased' width='164'>
      iVBORw0KGgoAAAANSUhEUgAAAKQAAACkCAYAAAAZtYVBAAAACXBIWXMAABYlAAAWJQFJUiTw
      AAAHKklEQVR4nO3YQWib5x3H8b9Ge+gLBWclWDTzlBa7yTDu0tazITEu9eawuenoiiE17lhT
      jHLwQUuYd8gGy6E6BTaNHTaXdR3MgzBCNh2iGncEp0lTvJpmtWO8JllceQ6zVSYPq6sOMvx2
      sOw4llyHJOC/o+8HHrBePX7fF+nLq+d9Q5JkgBNf2uwTAFYjSLhCkHDlgbUbQqHQZpwHYGZc
      IeEMQcIVgoQrBAlXCBKuECRcIUi4QpBwhSDhCkHCFYKEKwQJVwgSrhAkXCFIuEKQcIUg4QpB
      whWChCsECVcIEq4QJFwhSLhCkHCFIOEKQcIVgoQrBAlXCBKuECRcIUi4QpBwhSDhCkHCFYKE
      KwQJVwgSrhAkXCFIuEKQcIUg4QpBwhWChCsECVcIEq4QJFwhSLhCkHCFIOEKQcIVgoQrBAlX
      CBKuECRcIUi4QpBwhSDhCkHCFYKEKwQJVwgSrhAkXCFIuEKQcIUg4QpBwhWChCsECVcIEq4Q
      JFwhSLhCkHCFIOEKQcIVgoQrBAlXCBKuVGSQwVO9NjA6bbmCTCpY7tMJG4y/aJFbZ1nvkEwq
      N1IWvZ0DVTXZ9fn80v8UcjY9OmCxpqoy02KrzkeWn5+wwXin1QUlM60pNmCj0zkrSCblbX5i
      0OKddVYydavSGmZ2X4+gNaHJfFrJWJtqqkxmgar3HNCx07/U92+Z26pfTc3qzY47O0744Fv6
      Zy6jttpqBWayqnodeH1Y2cKkTuzd6Hy61D+eVzYVVWRln4FaE5PKp5OKtdWoykwWVGtPV7/G
      81mlopFN/2zvyaisINvVP3ObX17QqyGdV1/4zo6196f96nsqWLM9UPepBc2+2VF8HVbfeWks
      3lC6j3BUqYUZ9bcvv+7TeY0p3lB6rHA0pYWZfrVv+ud79+MBqyBB92Hryv7a9r2R3nhy426r
      m7tiidk7O9bF1w/bxZKtn9u//v0fe+Sr1cXXj9uOsNlMerx0B7OX7crcDnviseWpOyxsM1Z+
      6hWb2/GEPVb61pZTUWvIF17Yb3Nnz1iZ77RE0LDLdl79h314L08g6LAffO8r9t7w28UNf7cP
      PsrZk80dpWvAyD57Zue4XXp/eeoH9lHuSWvuKF0tRvY9YzvHL9n7Je9sQZXzk71Lxz+Uhn7U
      op7EoCY+zakgScprfuK0Yk1Vt8xvPDG55pPJa/76qAZiTUvrt9sY3zn6u5W/g7pXdTJdWLMu
      NFkkqmQmo5FEl+qX15AtMSXTGY0cb11afxZHJJpUJjOiRFf9yhqyJZZUOjOi461rlwdbc1TQ
      FfIRq3rYbHHhgv32h9+2+u0P24OhkIVCD9m2+lfs6uHLVkhFV65Uo31fs1AotGo8ZNseb7RX
      /vIN+9PCgp08uPER3/75a3bsnYwV8uP2i6+/Z69FHrQvd7xhqxcMQeRRCy/m7MbUnC0sb/ws
      Y1OzZuHdNbb95kyLPBq2xdwNm5pbmWmfZaZs1sK2u2a73Rcq5wppiqakyRON5d+PpqSrCe3d
      cD+Beoe+YD+rR6Rb2ZG4vlW13pyXNJBd0Knucle3BsXHCho+El56/dKAsgun1B2U2U9DXGOF
      YR25wxswT6OCrpBm5/52yXZ/84Dtugf7yv8vt8GMBjv+599b83M/sb/+d50pe1utedsFG/rj
      52XeHLczZz+xZ9u/W5zabNsuDFn5qWfs7CfPWnHqllZRQX78mz/YuYYe+3HJjUFg3ftbbH7k
      3eKd8X7rfnWdh82RXnv5uWv27tDHX3isoPtndrQ2aVfLBbTsetpuLD5tLS+WO1KDPd9Wa9eu
      XC5OvWGLT7dY+anPW1vtNStO3doq6SfbzNRw9Jyy2VU3BlX16kqMKJtNKRq5+VP6ViavzMV+
      9bTVqjowmVWppu2Y3snklTl9SOFV+wwfGVZBkzrReHPboWRh1fPG9cbSw+5CdkT9PS3F4xQf
      1CfTKmSTOrT8Mxy0KjFZUHakXz0txYftQbX2HDimZLqgbPLWc9qyo9KCNAtU15nQueniXXYh
      p+lzCXXWrVnHBdVqiQ1o9Pq88pKkgnLT5e6yGxQf05ogltaZ60pF15xPXIMTy8eRCrlpjQ7E
      1LR27RnUqTM+qIn5lZnrnNMWHpUX5D0e7f2aWX0lY9zdIMi7GYG6T6V18uD98QzQwwgVI1wR
      CoUM2CwVdZcN/wgSrhAkXCFIuEKQcIUg4QpBwhWChCsECVcIEq4QJFwhSLhCkHCFIOEKQcIV
      goQrBAlXCBKuECRcIUi4QpBwhSDhCkHCFYKEKwQJVwgSrhAkXCFIuEKQcIUg4QpBwhWChCsE
      CVcIEq4QJFwhSLhCkHCFIOEKQcIVgoQrBAlXCBKuECRcIUi4QpBwhSDhCkHCFYKEKwQJVwgS
      rhAkXCFIuEKQcIUg4QpBwhWChCsECVcIEq4QJFwhSLhCkHCFIOEKQcIVgoQrBAlXCBKuECRc
      +T+BTpqIozlf3QAAAABJRU5ErkJggg==
    </thumbnail>
    <thumbnail height='192' name='Introduction' width='192'>
      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
    </thumbnail>
    <thumbnail height='192' name='Map cases' width='192'>
      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
    </thumbnail>
    <thumbnail height='164' name='Number (Total)' width='164'>
      iVBORw0KGgoAAAANSUhEUgAAAKQAAACkCAYAAAAZtYVBAAAACXBIWXMAABYlAAAWJQFJUiTw
      AAAGIElEQVR4nO3ZQWicdR7G8V/Ei+/FAcXkYIiHDhWWgELMIUjAUC2GHnQppJLDGgjjISxR
      loAEWXpoDpLLSC9GCAV3WCNU2VxmS3opdS0UQi0tYWRDI9XsNjvihE0gc3gPj4fUNp3OdKbW
      2qed7wd+h877552Xd75935k3HZIUgInHHvQBAHsRJKwQJKw8XvtCR0fHgzgOICK4QsIMQcIK
      QcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIK
      QcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIK
      QcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIK
      QcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIKQcIK
      QcIKQcIKQcJK+wWZ6Y/JwnKsbVZDUijdju+XCzHZn7llWZI9GNOfnI2Va5tRlUJSVDfXYrkw
      GTVLm+uZiKUthbQa+YHajUlMLO3u//YpRq5mbfbwTJxa+TG201+OaSVOzRyObHLXZ8KTakTE
      IztdIyd0Zbusc3PjGtrXqSRCkfmDDh07o0pa0uzAzbW5xbIuFqZ16KVuZSIUkajzhbeUP19R
      WsprMGn1fRONLJRVms2rqFXlB2q3D+r4dxuaH262nwF9cK6s7StfavrQS+rOXD+ml8f1WSlV
      ZXFMXQbn+J6nnYIc+GBOUy8mdaMZPbmljfnhG68lSb11oUje0KcbW1oYae09k+F5ra/PazjJ
      1Q8ymdCSvtJUV5N9JWOanXtDPfW29c7oUiv7eAimrW7Z5469E7Pf7NTZshM/XPspnnq68+Yr
      O/XWRcROJf5ffSKeaPEW+eFHb8a//vLnKDbYXfQ9H9n//TtWNprsaOdETL3zj7hab9uV/8ZG
      PB3PPNvaMTlrqyAbSobjT28+G1+f+WfTpT2592P0yS/i75+3tuvR1ffj3c8b1RiR9O6P51a/
      jQutHmu9Y5o4Eq/852wsLd/DTly00y273iTZt7VwNVWlmKt/O4xQJJ3aNzSu/Kkr2i6fbnDb
      v31e/+vXmur55d/1b9l9s6WaT6CqzbVlFSb7r393vdNkdGDmvCppSfnB1o7JftoyyEy/pk+X
      lVYva+5wdvfHTZMPvvv5IR05VtDF8rYuN/out2e6xhZVWT2+57UG3yEbTc+ElrbqfVdNlD08
      p8vVVOXT0+rPGJzP33LaLsie0d0r4vkZHfg1H2bmgD5eTXXmva7Ga5Jhza9XtDCy96p1l0FG
      ooklqTTbd8trg0fPq5Je1cLbrfxHeginvYLs1dELqSrFCWVbfmxz+wzkV6VirvGaXLH2tN6m
      mGv2PrtBXji6/8ZryciCKmlJxw9kDM7lfZp2CjIZPamtrZMabRZjklGm4ZrdR0Trc6/e5fvX
      u0K+ptFGV7qeKX2V7l3fq5lL0qWZ3gd+Hu/rtFOQY4vpLc8aG85AXqXyRRWOHbn5AD1Cme4h
      jf/tsqqVonI9N9d3vXdGqUqa7bvTfusF+UedKFdVPjen8aF96kxCERl1D03rdLmq8pd7Hnb3
      zar0iDxrvOO0T5C7t8Am99Eba7MHp/XJ2RVd+3Fb6fXN1c01LRemdTC797vh7pWr+V9KGj0Y
      79TLkwUtr22qKklKtf19nV/Zg8f13R0P/m6+nxpP+wR5n+bVOa1XFjX2qF+5fq8hyHuZRKMn
      r9b8mmbuZTquR3hDR0dHAA8KfzqEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKE
      FYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKE
      FYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKE
      FYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKEFYKE
      FYKElZ8BIkB3i/yIbjgAAAAASUVORK5CYII=
    </thumbnail>
    <thumbnail height='192' name='Total Cases' width='192'>
      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
    </thumbnail>
  </thumbnails>
</workbook>
