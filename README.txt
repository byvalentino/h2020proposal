%% Copyright (c) 2010, Giacomo Indiveri
%%
%%  This latex class is free software: you can redistribute it and/or modify
%%  it under the terms of the GNU General Public License as published by
%%  the Free Software Foundation, either version 3 of the License, or
%%  (at your option) any later version.
%%
%%  h2020proposal.cls is distributed in the hope that it will be useful,
%%  but WITHOUT ANY WARRANTY; without even the implied warranty of
%%  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
%%  GNU General Public License for more details.
%%
%%  You should have received a copy of the GNU General Public License
%%  along with h2020proposal.cls.  If not, see <http://www.gnu.org/licenses/>.
%%
%% Contributors: Elisabetta Chicca
%%
%% Disclaimer: The proposal templates provided that make use of this class are based on the 
%% documents provided by the EU Participants Portal 
%%
%% Use the original sources and the http://ec.europa.eu/ documentation for reference. We make no
%% representations or warranties of any kind, express or implied, about the completeness, accuracy,
%% reliability, suitability or availability with respect to the original template.
%% In no event will we be liable for any loss or damage including without limitation, indirect or
%% consequential loss or damage, or any loss or damage whatsoever arising out of, or in connection
%% with, the use of this template and/or class.
%%
%% The h2020proposal makes use of the memoir class. Read the optimum memman documentation for
%% info on how to customize your proposal.


Dear h2020proposal.cls user,

I hope this LaTeX class will be as useful to you as it has been for me. I managed to write several successful proposals with it, with large teams and sometimes very large documents.

If you do use it to write a real H2020 proposal, please send me an email: giacomo@ini.uzh.ch to acknowledge this. I would like to keep a record of how many times the class has been used.

Good luck with your submission!

giacomo



Brief description:
~~~~~~~~~~~~~~~~~~~~
1. h2020proposal.cls:   (version 1.0 from 2015/09/20)
   The LaTeX2e class that contains all macros and commands for cross-referencing and generating the tables required for the EU RIA H2020 proposal documents.


2. template-fet.tex:   (version 1.0 from 2015/09/20)
   Example H2020 FET proposal with instructions copied from EU provided word document template, available on the EU H2020 Participant Portal.

3. template-ict.tex:   (version 1.0 from 2015/09/20)
   Example H2020 ICT proposal with instructions copied from EU provided pdf guidelines, available on the EU H2020 Participant Portal.

Known users:
~~~~~~~~~~~~
University of Zurich, Institute of Neuroinformatics, Switzerland, Giacomo Indiveri (2015)
University of Bielefeld, CITEC, Germany, Elisabetta Chicca (2015,2016)
Fundació Privada per a la Xarxa Oberta, Lliure i Neutral guifi.net, and  Universitat Politècnica de Catalunya, Spain, Roger Baig Viñas (2016)
University of Edingburgh, School of Mathematics, UK, Chris Sangwin (2016)
Budapest University of Technology and Economics, Hungary, Tamas Csapo (2016)
Thales Research and Technology, Delft, Netherlands, Thomas Quillinan (2016)
Dresden Universiy, Dresden, Germany, Najeeb ul Hassan (2016)
AIT Austrian Institute of Technology GmbH, Donau-City-Straße 1, 1220 Vienna, Austria, Christoph Strieck (2017)

Tips and changes:
-----------------
Use \input for including all WP descriptions in text (instead of \input for the first and \include for the others), to avoid the creation of new-page after each WP.

% Memoir commands for compact layout
\setbeforesecskip{-0.5ex plus -.5ex minus -0.5ex}
\setaftersecskip{0.5ex plus 1ex}
\setbeforesubsecskip{-0.5ex plus -.5ex minus -0.5ex}
\setaftersubsecskip{0.5ex plus 0.5ex}
\setbeforesubsubsecskip{-0.5ex plus -.5ex minus -0.5ex}
\setaftersubsubsecskip{0.5ex plus 0.5ex}
\setlength\beforechapskip{0ex}
\setlength\afterchapskip{0ex}
% Compact bib
\setlength{\bibitemsep}{-\parsep}
% Frames
\setlength{\topsep}{0pt}

