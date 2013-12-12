Java-10.2
=======
import java.util.*;

public class Persoon 
{
	private String naam;
	private double budget;
	private ArrayList<Computer>bezittingen;
	
	public Persoon(String nm, double bud)
	{
		naam = nm;
		budget = bud;
		bezittingen = new ArrayList<Computer>();
	}
	public boolean koop(Computer c)
	{
		for (koop k: bezittingen)
		{
			if (k.getBudget().equals(HuidigeWaarde))
			{
				return true;
			}
		}
	}
	public boolean bezit(String mk)
	{
		for (bezit b: bezittingen)
		{
			if ()
		}
	}
	public boolean verkoop(Computer c, Persoon koper)
	{
		for (verkoop v: bezittingen)
		{
			if()
		}
	}
	public Computer zoek(String mk)
	{
		for (Computer c: bezittingen)
		{
			if (c.bezit().equals (mk))
			{
				return c;
			}
		}
		return null;
	}
	public void verwijder(String mk)
	{
		bezittingen.remove(mk);
	}
	public double getBudget()
	{
		return budget;
	}
	public String toString()
	{
		String s = "";
		return s;
	}
}
