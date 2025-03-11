# DLL Symbols
## dumpbin
```
Microsoft (R) COFF/PE Dumper Version 14.43.34808.0
Copyright (C) Microsoft Corporation.  All rights reserved.


Dump of file .\RedAlert.dll

File Type: DLL

  Section contains the following exports for RedAlert.dll

    00000000 characteristics
    FFFFFFFF time date stamp
        0.00 version
           1 ordinal base
          44 number of functions
          44 number of names

    ordinal hint RVA      name

          1    0 00043760 CNC_Add_Mod_Path = _CNC_Add_Mod_Path
          2    1 000437D0 CNC_Advance_Instance = _CNC_Advance_Instance
          3    2 00043C80 CNC_Clear_Object_Selection = _CNC_Clear_Object_Selection
          4    3 00043CB0 CNC_Config = _CNC_Config
          5    4 0001AAF0 CNC_Editor_Cleanup = ?Cost_Of@ObjectTypeClass@@UBEHXZ (public: virtual int __thiscall ObjectTypeClass::Cost_Of(void)const )
          6    5 00046720 CNC_Editor_Clear_Map = _CNC_Editor_Clear_Map
          7    6 00046750 CNC_Editor_Get_Cell_Data = _CNC_Editor_Get_Cell_Data
          8    7 000467E0 CNC_Editor_Get_Cell_Data_By_Index = _CNC_Editor_Get_Cell_Data_By_Index
          9    8 00046860 CNC_Editor_Get_Cell_Texture_Buffer = _CNC_Editor_Get_Cell_Texture_Buffer
         10    9 00046B40 CNC_Editor_Get_Map_Stats = _CNC_Editor_Get_Map_Stats
         11    A 00046BA0 CNC_Editor_Get_Scenario_Names = _CNC_Editor_Get_Scenario_Names
         12    B 00046DB0 CNC_Editor_Get_Template_Data = _CNC_Editor_Get_Template_Data
         13    C 00046E80 CNC_Editor_Load_Map = _CNC_Editor_Load_Map
         14    D 00047070 CNC_Editor_Load_Map_By_Scenario_Name = _CNC_Editor_Load_Map_By_Scenario_Name
         15    E 00047120 CNC_Editor_Startup = _CNC_Editor_Startup
         16    F 00043CC0 CNC_Get_Game_State = _CNC_Get_Game_State
         17   10 00043FC0 CNC_Get_Palette = _CNC_Get_Palette
         18   11 00043FE0 CNC_Get_Start_Game_Info = _CNC_Get_Start_Game_Info
         19   12 00044020 CNC_Get_Visible_Page = _CNC_Get_Visible_Page
         20   13 000440C0 CNC_Handle_Beacon_Request = _CNC_Handle_Beacon_Request
         21   14 00044270 CNC_Handle_ControlGroup_Request = _CNC_Handle_ControlGroup_Request
         22   15 000442D0 CNC_Handle_Debug_Request = _CNC_Handle_Debug_Request
         23   16 000128B0 CNC_Handle_Game_Request = ?AI@AbstractClass@@UAEXXZ (public: virtual void __thiscall AbstractClass::AI(void))
         24   17 00044600 CNC_Handle_Game_Settings_Request = _CNC_Handle_Game_Settings_Request
         25   18 00044650 CNC_Handle_Human_Team_Wins = _CNC_Handle_Human_Team_Wins
         26   19 00044760 CNC_Handle_Input = _CNC_Handle_Input
         27   1A 00044B50 CNC_Handle_Player_Switch_To_AI = _CNC_Handle_Player_Switch_To_AI
         28   1B 00044BE0 CNC_Handle_Sidebar_Request = _CNC_Handle_Sidebar_Request
         29   1C 00044E30 CNC_Handle_Structure_Request = _CNC_Handle_Structure_Request
         30   1D 00044FE0 CNC_Handle_SuperWeapon_Request = _CNC_Handle_SuperWeapon_Request
         31   1E 00045080 CNC_Handle_Unit_Request = _CNC_Handle_Unit_Request
         32   1F 000453F0 CNC_Init = _CNC_Init
         33   20 00045420 CNC_Read_INI = _CNC_Read_INI
         34   21 00045600 CNC_Restore_Carryover_Objects = _CNC_Restore_Carryover_Objects
         35   22 000456A0 CNC_Save_Load = _CNC_Save_Load
         36   23 00045800 CNC_Select_Object = _CNC_Select_Object
         37   24 00045AC0 CNC_Set_Difficulty = _CNC_Set_Difficulty
         38   25 00045AE0 CNC_Set_Home_Cell = _CNC_Set_Home_Cell
         39   26 00045B70 CNC_Set_Multiplayer_Data = _CNC_Set_Multiplayer_Data
         40   27 00045DD0 CNC_Start_Custom_Instance = _CNC_Start_Custom_Instance
         41   28 00046180 CNC_Start_Instance = _CNC_Start_Instance
         42   29 000461B0 CNC_Start_Instance_Variation = _CNC_Start_Instance_Variation
         43   2A 000464C0 CNC_Start_Mission_Timer = _CNC_Start_Mission_Timer
         44   2B 00046530 CNC_Version = _CNC_Version

  Summary

      308000 .data
        1000 .fptable
       27000 .rdata
       12000 .reloc
        1000 .rsrc
       F4000 .text
        1000 code
```
## dependencies