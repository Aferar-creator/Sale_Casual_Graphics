Winter Stickman – Characters, Outfits & Props (Casual Vertex Color)
Render Pipeline: URP (Universal Render Pipeline)

Instal shader
-- Instaled package Universal RP
-- Set in Project Settings > Graphics > Scriptable Render Pipeline Settings set "VertexColor"
-- all is done

LitVertexColor Shader

	- Supports real-time lighting and shadows,
	- Physically-correct lighting,
	- Responds to scene lights

UnLitVertexColor Shader

	- Ignores lights and shadows,
	- Always looks the same regardless of scene lighting,

Both shaders use only vertex colors set up in your 3D package.
For performance reasons, UV mapping is not required.

 Compatibility,
	- Compatible with URP (Universal Render Pipeline),
	- Not compatible with Built-in RP,
	- No textures or UVs,
	- No C# code included