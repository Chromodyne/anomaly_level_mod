=================================================
=                                               =
=           Zone Experience Project             =
=               Version 0.01                    =
=          Updated: 03/03/21 @ 12:39            =
=                                               =
=================================================

Creator/Developer: Chromodyne

Contact Info/Support
      Email: chromodyne(at)protonmail.com
      Discord: Chromodyne#6925
      Discord Server: https://discord.gg/cTWduNNS (I can also be found on the official Anomaly Discord.)
      Patreon: 

==============
=INSTALLATION=
==============

    1. Extract the gamedata folder in the archive to your Anomaly installation directory.
    2. Enjoy!

=========  
=GENERAL=
=========

NOTICE: This addon is in very early stages of development. Most planned features are not yet implemented.
        Please keep this in mind when using this addon in its current state.

This addon adds an experience and leveling system to S.T.A.L.K.E.R. Anomaly. Currently it is very rudimentary; however, plans are to make
it much more in-depth in the coming months. In its current state, when the player kills NPCs or mutants in the Zone they gain experience points. 
After gaining a certain amount of these points the player will level-up, increasing their stats. 

The stats gained on level up, exp required per level, etc can be found and modified in:

    \gamedata\configs\levelmod\level_system.ltx

The experience values for each monster can be found and modified in:

    \gamedata\configs\levelmod\level_experience.ltx

=======
= KEYS=
=======

Currently there is no proper UI for the mod and the key bindings are not customizable.

Show current exp

================
= KNOWN ISSUES =
================

    1. Max carry weight stat gains MAY reset if you mess with the max weight slider in the difficulty options. (Fix underway.)
    (^^^ A partial fix is implemented but there are certain situations where it may fail. Recommend leaving this slider alone after char creation for now. - Chromodyne)
    2. NPCs give a set amount of experience on kill. Separate values will be implemented in an upcoming update.


==================
=PLANNED FEATURES=
==================

    NOTICE: All planned features are subject to change or cancellation. Timeframes given are  ROUGH estimates of when 
    I hope to have these features added in some form. These estimates may be completely wrong.

    =============
    =NEAR FUTURE=
    =============

    1. Customizable keybinds, etc. through in game options menu and config.
        No longer will the keybinds be hardcoded. 

    2. NPC experience gains are based on the ascertained difficulty on the NPC. (Faction, gear they have, etc.)

    3. Full tweakable difficulty system.
        e.g. Higher difficulty levels will reduce stat gains on level up. Currently can be done manually through config.

    4. Experience point loss on ironman death. (Optional)
        This will only take effect if the player has more than one remaining life.

    ==========
    =SOON(TM)=
    ==========

    1. Custom User Interface (UI)

        Experience bar, level indicator, etc. If possible, a PDA tab will be implemented with further information.

    ===========
    =LONG TERM=
    ===========

    1. SKILL BASED EXPERIENCE SYSTEM / Individual experience bars.

        This is the major milestone I will be moving towards.  A seperate experience pool for skills ala Tarkov. 
        i.e. Strength, Stamina, Restances, Toughness, etc. that level up when doing relevant activities and tasks.

===============================
=COPYRIGHT/LICENSE/LEGAL STUFF=
===============================

    Copyright 2021 Chromodyne - All Rights Reserved

    Chromodyne, henceforth 'the creator', is the sole owner of this addon.
    Publishing modifications or forks of this addon are forbidden without the express, written permission of the creator.
    Use of this addon as a basis for another addon is forbidden without the express, written permision of the creator.
    This addon may, however, be freely redistributed without modification in its original state with 
    proper attribution given to the creator.

    THE ADDON IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR 
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, 
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL 
    THE CREATORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER 
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, 
    OUT OF OR IN CONNECTION WITH THE ADDON OR THE USE OR OTHER DEALINGS IN 
    THE ADDON.