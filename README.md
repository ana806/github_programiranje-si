# github_programiranje-si
#include<iostream>
#include<string>
using namespace std;


void star_warsime(string ime, string prezime, string djevojacko_prezime, string grad_rodjenja){


string imei,gradi,starwarsname;
imei=ime.substr(0,3);
gradi=grad_rodjenja.substr(0,2);
starwarsname=imei+gradi;


string imen, grrodjn, prezimen;

imen=djevojacko_prezime.substr(0,2);
grrodjn=grad_rodjenja.substr(0,3);

prezimen=imen+grrodjn;

cout<<"Vase StarWars ime glasi:"<<starwarsname<<" "<<prezimen<<endl;
}


int main()
{
  string ime,prezime,djevojacko_prezime,grad_rodjenja;
  cout<<"Unesite vase ime ";
  cin>>ime;
  cout<<"Unesite vase prezime ";
  cin>>prezime;
  cout<<"Unesite nvaše djevojacko prezime ";
  cin>>djevojacko_prezime;
  cout<<"Unesite grad u koejem ste rodjeni ";
  cin>>grad_rodjenja;
  cout<<endl;


 star_warsime(ime, prezime, djevojacko_prezime, grad_rodjenja);


}
