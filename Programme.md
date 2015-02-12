# Calculatrice-C-
#include<iostream>
#include <cstdint>
using namespace std; 

int main ()
{
	int operateur = 0; 
	int type = 0;
	int OperandeA;
	int OperandeB;
	
	//Premier menu choix de l'opérateur 

	printf("\t\t\t Calculatrice");
	printf("\n\n");
	printf("\n\n");
	printf("\n\n");
	printf("1) + \n");
	printf("2) - \n");
	printf("3) * \n");
	printf("4) % \n");
	printf("5) modulo \n");
	printf("\n\n");

	printf("Choisissez votre type d'operation");
	scanf("%int, &operateur");

	// Second menu en fonction du choix de l'opérateur

	if(operateur==1) 
	{
		printf("1.1) int_32t \n");
		printf("1.2) int_64t \n");
		printf("1.3) float \n");
		printf("1.4) double \n");
	}

	else 
	
		if(operateur==2)
		{
			printf("2.1) int_32t \n");
		printf("2.2) int_64t \n");
		printf("2.3) float \n");
		printf("2.4) double \n");

		}
	
		
		else

		if(operateur==3)
		{
			printf("1.1) int_32t \n");
		printf("1.1) int_64t \n");
		printf("1.1) float \n");
		printf("1.1) double \n");

		}

		else

		if(operateur==4)
		{
			printf("4.1 int_32t \n");
		printf("4.2 int_64t \n");
		printf("4.3 float \n");
		printf("4.4 double \n");

		}

		else

		if(operateur==5)
		{
			printf("5.1 int_32t \n");
		printf("5.2 int_64t \n");
		printf("5.3 float \n");
		printf("5.4 double \n");

		}
	
	
		scanf("%int, type");

		// Si choix menu 1 +

		if(type==1.1)
		{
			int32_t ajouter (int32_t OperandeA, int32_t OperandeB);

			{
				return OperandeA + OperandeB;
			}
		}

		else
		
		if(type==1.2)
		{
			int64_t ajouter (int64_t OperandeA, int64_t OperandeB);

			{
				return OperandeA + OperandeB;
			}
		}

		

		else 
		
		if(type==1.3)
		{
			 float ajouter (float OperandeA, float OperandeB);

			{
				return OperandeA + OperandeB;
			}
		}

		else 

		if(type==1.4)
		{
			double ajouter (double OperandeA, double OperandeB);

			{
				return OperandeA + OperandeB;
			}
		}

		// Si choix menu 2 -
		
		if(type==2.1)
		{
			int32_t soustraire (int32_t OperandeA, int32_t OperandeB);

			{
				return OperandeA - OperandeB;
			}
		}

		else
		
		if(type==2.2)
		{
			int64_t soustraire (int64_t OperandeA, int64_t OperandeB);

			{
				return OperandeA - OperandeB;
			}
		}
		
		else 
		
		if(type==2.3)
		{
			 float soustraire (float OperandeA, float OperandeB);

			{
				return OperandeA - OperandeB;
			}
		}

		else 

		if(type==2.4)
		{
			double soustraire (double OperandeA, double OperandeB);

			{
				return OperandeA - OperandeB;
			}
		}

		// Si choix menu 3 *
		
		if(type==3.1)
		{
			int32_t multiplier (int32_t OperandeA, int32_t OperandeB);

			{
				return OperandeA * OperandeB;
			}
		}

		else
		
		if(type==3.2)
		{
			int64_t multiplier (int64_t OperandeA, int64_t OperandeB);

			{
				return OperandeA * OperandeB;
			}
		}
		
		else 
		
		if(type==3.3)
		{
			 float multiplier (float OperandeA, float OperandeB);

			{
				return OperandeA * OperandeB;
			}
		}

		else 

		if(type==3.4)
		{
			double multiplier (double OperandeA, double OperandeB);

			{
				return OperandeA * OperandeB;
			}
		}

		// Si choix menu 4 /
		
		if(type==4.1)
		{
			int32_t diviser (int32_t OperandeA, int32_t OperandeB);

			{
				return OperandeA / OperandeB;
			}
		}

		else
		
		if(type==4.2)
		{
			int64_t diviser (int64_t OperandeA, int64_t OperandeB);

			{
				return OperandeA / OperandeB;
			}
		}

		else 
		
		if(type==4.3)
		{
			 float diviser (float OperandeA, float OperandeB);

			{
				return OperandeA / OperandeB;
			}
		}

		else 

		if(type==4.4)
		{
			double diviser (double OperandeA, double OperandeB);

			{
				return OperandeA / OperandeB;
			}
		}

		// Si choix menu 5 modulo
		
		if(type==2.1)
		{
			int32_t modulo (int32_t OperandeA, int32_t OperandeB);

			{
				return OperandeA % OperandeB;
			}
		}

		else
		
		if(type==2.2)
		{
			int64_t ajouter (int64_t OperandeA, int64_t OperandeB);

			{
				return OperandeA % OperandeB;
			}
		}

		printf("Cordialement Augustin Ballot-Ragaru STS1");

		return 0; 
		}
