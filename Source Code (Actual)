use strict;
#use warnings; Issues a warning about line nine being 'useless'; Ignore if encountered

#Sanghelli Name Generator

#Define Arrays
my @First = qw( Thel Avu Forze Raia Bero Thon Reff Zef Rho Rtas Gek Ripa Jul Levu Kimal Relon Gusay Jalam Thun Naxan Dural Asum Gmal ); #The first name list 
my @Last = qw( 'Vadam 'Mdama 'Telcam 'Sum 'Kusov 'Taralum 'Vadum 'Moram 'Refum 'Talam 'Trahl 'Barutam 'Lhar 'Lodam ); #The last name list

#Define Subroutines
sub Generate { #Generates the names
system ("cls");
print $First[int(rand(23))]; #Randomly picks the first name form the Array @First
print " "; #Provides a space between the First and Last randomly generated name
print $Last[int(rand(14))]; #Randomly picks the last name from the Array @Last
print " \n"; #Finishes of the name and ensures an enter to prevent any wierd combined messages (Oh the joys of PERL)
system ("pause > nul"); #Pauses the script from heading back to the main menu until the user is ready; The  > nul part is to prevent the 'Press any key to continue...' Bullshit (Oh the joys of batch)
&Main; #Goes back to the main menu
}

sub Disclaimer { #Disclaimer command
system("cls");
print "\n";
print "Sangheili name generator is a random name generator\n";
print "Copyright (C) 2015  Charles Hildebrandt\n";
print "This program is free software: you can redistribute it and/or modify\n";
print "it under the terms of the GNU General Public License as published by\n";
print "the Free Software Foundation, either version 3 of the License, or\n";
print "any later version.\n";
print "\n";
print "This program is distributed in the hope that it will be useful,\n";
print "but WITHOUT ANY WARRANTY; without even the implied warranty of\n";
print "MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the\n";
print "GNU General Public License for more details.\n";
print "\n";
print "You should have received a copy of the GNU General Public License\n";
print "along with this program.  If not, see <http://www.gnu.org/licenses/>.\n";
system("Pause > nul");
&Main;
}

sub Main { #The Main Menu
system ("Title Sangheili Name Generator");
system ("cls");
print "Random Sanghelli Name Generator\n";
print "ver 1.0.0\n";
print " \n";
print "Do you want to Generate a name (1), Read the disclaimer (2), or exit (3)?\n";
my $Input = <>;
chomp $Input;
if ($Input == 1) {
	&Generate;
} elsif ($Input == 2) {
&Disclaimer;
} elsif ($Input == 3) {
	exit;
} else {
print "That is not an option\n";
system ("pause > nul");
&Main;
}
}

&Main; #Launches the main menu
